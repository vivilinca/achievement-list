# Achievement List

一个给孩子用的 iPad 横屏每日任务表（Unicorn Routine）。把活动拖进“今天”一列来记分，完成学习任务赚积分，积分够了才能解锁零食、游戏和 iPad 时间。

## 使用
直接用浏览器打开 `index.html` 即可，无需安装。建议在 iPad 上横屏使用，可“添加到主屏幕”。

## 积分规则
| 活动 | 分数 |
|---|---|
| Typing Practice / Math | +4 |
| English Reading / Chinese Reading | +5 |
| English Writing / Chinese Writing | +3 |
| Exercise / Craft / Painting | +1 |
| Snack / Games / iPad Time | −5（当天超过 13 分才解锁） |

- 每天午夜，当天没做的加分项各扣 1 分。
- 记录保留约 35 天。数据保存在浏览器本地（localStorage），不同设备之间不同步。

## 隐藏功能
换装（Dress Up）和宝箱奖励掉落目前是隐藏的。把 `index.html` 里的 `const REWARDS = false;` 改成 `true` 即可恢复。
