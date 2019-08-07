#  [emoji-java](https://github.com/vdurmont/emoji-java)

[fix it](https://github.com/vdurmont/emoji-java/issues/123)
[fix it](https://github.com/vdurmont/emoji-java/issues/130)

[![Build Status](https://travis-ci.org/vdurmont/emoji-java.svg?branch=master)](https://travis-ci.org/vdurmont/emoji-java)
[![Coverage Status](https://img.shields.io/coveralls/vdurmont/emoji-java.svg)](https://coveralls.io/r/vdurmont/emoji-java?branch=master)
[![License Info](http://img.shields.io/badge/license-The%20MIT%20License-brightgreen.svg)](https://github.com/vdurmont/emoji-java/blob/master/LICENSE.md)

*The missing emoji library for java.*

**emoji-java** is a lightweight java library that helps you use Emojis in your java applications.

## How to get it?

##### Via Maven:
```xml
<dependency>
  <groupId>com.github.sinboun</groupId>
  <artifactId>emoji-java</artifactId>
  <version>1.0.1</version>
</dependency>
```

You can also download the project, build it with `mvn clean install` and add the generated jar to your buildpath.

##### Via Gradle:
```gradle
compile 'com.github.sinboun:emoji-java:1.0.1'
```

## How to use it?
see it：[wiki](https://github.com/vdurmont/emoji-java)
```xml
String alias = EmojiUtil.toAlias("😄");//:smile:
```

```xml
String emoji = EmojiUtil.toUnicode(":smile:");//😄
```

```xml
EmojiUtil.containsEmoji("👍hello")； return true ；[fix it](https://github.com/vdurmont/emoji-java/issues/123)
```

## Credits

**emoji-java** originally used the data provided by the [github/gemoji project](https://github.com/github/gemoji). It is still based on it but has evolved since.
