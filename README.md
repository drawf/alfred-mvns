# alfred-mvns
[![NPM](https://nodei.co/npm/alfred-mvns.png)](https://nodei.co/npm/alfred-mvns/)

## 变更

基于原版主要修改如下：
* 修复 Alfred4 安装失败问题（Error: Alfred preferences not found at location）
* 将默认使用 Gradle 而非 Maven
* 将 Gradle 依赖前缀修改为 implementation

## Install

*Requires [Node.js](https://nodejs.org) 4+ and the Alfred [Powerpack](https://www.alfredapp.com/powerpack/).*

~~- npm install `npm install -g alfred-mvns`~~

- npm install `npm install -g https://github.com/drawf/alfred-mvns.git`

- [download](https://github.com/xfslove/alfred-mvns/releases) workflow

## Usage

In Alfred, type `mvn`, and your query, to search for java libraries at maven central repository.

Select a item and press <kbd>enter</kbd> to copy `maven dependency` to clipboard.<br>

Hold <kbd>alt</kbd> and press <kbd>enter</kbd> to copy `gradle dependency` to clipboard.<br>

## Demo

![mvn.png](mvn.png)

press <kbd>enter</kbd> get:

```
<dependency>
  <groupId>org.nd4j</groupId>
  <artifactId>jackson</artifactId>
  <version>0.9.1</version>
</dependency>
```
Hold <kbd>alt</kbd> and press <kbd>enter</kbd> get:

```
compile 'org.nd4j:jackson:0.9.1'
```

## Related

- [alfy](https://github.com/sindresorhus/alfy) - Create Alfred workflows with ease


## License

MIT © 
