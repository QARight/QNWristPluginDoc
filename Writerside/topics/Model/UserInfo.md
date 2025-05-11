<show-structure depth="2"/>

# UserInfo

> 用户信息对象

## 成员变量

| 名称     | 类型            | 说明                  |
|--------|---------------|---------------------|
| year   | Int           | 出生日期 年              |
| month  | Int           | 出生日期 月              |
| day    | Int           | 出生日期 日              |
| height | Int           | 身高，单位cm             |
| weight | Int           | 体重 (单位：kg），该值需要x100 |
| gender | [](Gender.md) | 性别                  |

## 方法

### buildUserInfo

`静态方法` 创建一个UserInfo的对象

<code-block lang="Kotlin">
    fun buildUserInfo(
        year: Int,
        month: Int,
        day: Int,
        height: Int,
        weight: Int,
        gender: [[[Gender|Gender.md]]]
    ): UserInfo
</code-block>
