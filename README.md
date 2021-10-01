<h2 align="left"> Hi there 👋</h2>


<h3 align="left">🤵 About Me:</h3>

🌱 I am a student studying in 42Tokyo.

[![jaeskim's 42 status](https://badge42.herokuapp.com/api/stats/ktabe?cursus=42cursus)](https://github.com/JaeSeoKim/badge42)

 * * *  
<!-- <h3 align="left">📈 My Github stats:</h3>

[![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=kotatabe&show_icons=true&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=kotatabe&layout=compact&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats) -->

<!--- made by https://github.com/anuraghazra/github-readme-stats --->

# 最近の42での成果物

* 学生同士でペアを組みで, bash-like shellを実装
  * 簡潔な流れ
    1. シェルで受け取った文字列を単語分割
    2. 構文解析
      * 処理する優先順位をつけるため抽象構文木というデータ構造にして保存
    3. 実行
  * リンク[https://github.com/seipan1213/minishell]（https://github.com/seipan1213/minishell）
  * 利用した主な関数
    * 基本的なシステムコール関数（open, close, read, write, stat, lstat）
    * プロセス管理系（fork, waitpid, execve）
    * パイプ処理系（pipe, dup, dup2）
    * シグナル系（signal, sigaction, kill）
  * 実装した機能
    * ファイル入出力、リダイレクト（ヒアドキュメント可）、パイプ
    * builtinコマンド（echo, cd, pwd, export, unset, env, exit） 
  
