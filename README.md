# deno_hello

## 使い方
### インストール
```
$ deno install cli.ts
# or
$ deno install --name deno_hello https://raw.githubusercontent.com/ytkg/deno_hello/main/cli.ts
```

### コンパイル
```
$ deno compile cli.ts
# or
$ deno compile --output deno_hello https://raw.githubusercontent.com/ytkg/deno_hello/main/cli.ts
```

### パスを通す
```
$ echo 'export PATH="$HOME/.deno/bin:$PATH"' >> ~/.bash_profile
$ source ~/.bash_profile
```

### 実行
```
$ deno_hello
Hello, World!
```
