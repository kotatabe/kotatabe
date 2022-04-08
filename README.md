

# minishellの実装

## ペアプロで, bash-like shellを実装（https://github.com/seipan1213/minishell）
* 簡潔な流れ
1. シェルで受け取った文字列を単語分割
2. 構文解析（処理の優先順位付けのため抽象構文木というデータ構造にして保存）
3. 実行
* 利用した主な関数
  * 基本的なシステムコール関数（open, close, read, write, stat, lstat）
  * プロセス管理系（fork, waitpid, execve）
  * パイプ処理系（pipe, dup, dup2）
  * シグナル系（signal, sigaction, kill）
* 実装した機能
  * ファイル入出力、リダイレクト（ヒアドキュメント可）、パイプ
  * builtinコマンド（echo, cd, pwd, export, unset, env, exit） 
