# HELLO WORLD

## 1.新規プロジェクトの作成

新しいTerminalから以下のコマンドを実行する

```
cargo new {project name} [ENTER]
```

実行結果
```
PS C:\Users\proje\Desktop\nardimention\src\training> cargo new helloworld
     Created binary (application) `helloworld` package
```

## 2.プロジェクトのビルド

```
cargo build [ENTER]
```

実行結果
```
PS C:\Users\proje\Desktop\nardimention\src\training\helloworld> cargo build
    Finished dev [unoptimized + debuginfo] target(s) in 0.00s
```

## 3.プロジェクトのRun

```
cargo run 
```

実行結果
```
PS C:\Users\proje\Desktop\nardimention\src\training\helloworld> cargo run
    Finished dev [unoptimized + debuginfo] target(s) in 0.00s
     Running `target\debug\helloworld.exe`
Hello, world!
```