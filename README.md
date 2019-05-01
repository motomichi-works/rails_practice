# rails_tutorial_20190501
rails tutorialをやります。

以下のブログの手順で環境構築をしています。

http://motomichi-works.hatenablog.com/entry/2019/05/01/134603?_ga=2.43389989.14921413.1556627089-1312683509.1538152001



## 開発について

### サーバーを起動

```
docker-compose up -d
```



### サーバーを止める

```
docker-compose down
```



### bundle install

```
docker-compose run web bundle install
```



### rails

```
docker-compose run web rails hoge
```











