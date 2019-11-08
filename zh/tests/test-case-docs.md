# Test Cases 3D 场景测试使用说明
以下为测试例中每个测试场景的使用说明，其中**测试情景会说明实际需要测试的平台或者场景，没有说明就是预览 + 构建全平台全配置都需要正常显示，有说明只需要测试在某种特定配置有设置的情况下是否正常显示**。

## altas 场景
主要用于简单测试自动图集的构建情况，待完善
- 测试情景：勾选自动图集 + 构建后
- 预期效果：场景内显示一颗黄色星星即可
![atlas](./test-cases-docs/atlas.jpg)

## test-sub-packages 场景
主要用于简单测试子包构建后能否正常加载，以及放置在子包内的图集能否正常加载，待完善
- 测试情景：微信平台构建后
- 预期效果：界面上显示一只小羊，并且文字提示子包加载成功，图集加载成功即可
![subpackage](./test-cases-docs/subpackage.jpg)