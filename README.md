# かんばんりすと

ソフトウェアかんばん風のタスク管理アプリです。

## Installation

Ruby ver 1.9.2

```bash
$ git clone git@github.com:volpe28v/kanban-list.git
$ cd kanban-list
$ bundle
$ rake db:migrate
$ rails s
```

## Mail Setting

メール機能を利用する場合はメールアドレスとパスワードを環境変数に設定します。(Gmailのみ対応)
### 開発環境
```bash
$ MAIL_ADDR=xxxxxxx@gmail.com MAIL_PASSWORD=yyyyy rails s
```

### heroku
```bash
$ heroku config:add MAIL_ADDR=xxxxxxx@gmail.com MAIL_PASSWORD=yyyyy
```
## Demo
http://kanban-list.heroku.com/

```
サンプルアカウント
 mail: sample@kanban.list
 pass: sample
```

## License
(The MIT License)

Copyright (c) 2011 Naoki KODAMA <naoki.koda@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

