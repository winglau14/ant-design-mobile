---
category: Components
type: Components
chinese: 时间轴
english: Timeline
---


### 定义／Definition
垂直展示的时间流信息。

### 规则 / Rule
- 当有一系列信息需要从上至下按时间排列时；
- 需要有一条时间轴进行视觉上的串联时；


## API

```jsx
<Timeline>
  <Timeline.Item>创建服务现场 2015-09-01</Timeline.Item>
  <Timeline.Item>初步排除网络异常 2015-09-01</Timeline.Item>
  <Timeline.Item>技术测试异常 2015-09-01</Timeline.Item>
  <Timeline.Item>网络异常正在修复 2015-09-01</Timeline.Item>
</Timeline>
```

### Timeline.Item

时间轴的每一个节点。

| 参数      | 说明                                     | 类型       |  可选值 |默认值 |
|-----------|------------------------------------------|------------|-------|--------|
|  color   | 指定圆圈颜色。 | string | blue, red, green | blue     |
