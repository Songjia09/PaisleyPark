# Paisley Park

Paisley Park是一个标点预设工具，它允许您保存和加载随时使用的标点预设，而无需手动执行标点工作。（跟5.2版本新增的游戏内标点预设很像）

## 如何工作?

Paisley Park通过将程序集注入运行中的应用程序来工作。但是，Paisley Park不会对任何进程执行任何恶意代码，只注入代码来帮助调用进程中已经存在的函数。当应用程序正常关闭后，Paisley Park 会像什么都没发生一样，Paisley Park不会永久影响任何进程。如果您希望查看运行时注入的内容，可以查看 [这里](https://github.com/LeonBlade/PaisleyPark/blob/master/PaisleyPark/ViewModels/MainWindowViewModel.cs#L213).

## 我用这个会有麻烦吗?

Paisley Park 是通过逆向工程创建的，并通过修改运行进程的内存来实现。这意味着使用此工具是违反服务条款的。然而，Leon认为这个工具处于灰色地带，其他类似的第三方应用程序（如ACT）不会对任何人的体验产生负面影响，也不会给你带来任何比其他人更大的优势，也不会以任何方式作弊。这只是一个工具，它自动化了（在Leon看来）应该已经是一个现有特性的过程。

## 这个有毒么?

Paisley Park 100%安全！如果你有怀疑的话，这个项目的整个源代码都可以让你看一看。您的防病毒软件可能会触发假报毒。Paisley Park确实修改了正在运行的应用程序的内存。在粗略的水平上，这可能被看作是许多不同类型的病毒。请注意，病毒扫描软件并不总是彻底的，如果你有任何疑问或担忧，我再次请你自己查看代码。

## 这个软件会把我游戏干崩不?

Paisley Park 可能会干崩你的游戏, 但这种情况一般发生在游戏更新之后。 目前正在努力防止这种情况的发生，但要等到将来更新后才能使用。 意思就是在游戏更新之后不能用Paisley Park，你得等Paisley Park发布更新之后才能用。当然其他情况的崩溃可能也有，如果发生了请提交文件夹下的 `error.log` 和 `output.log` 然后我会尽力帮助你的。

## 这玩意咋用?

Paisely Park 目前是在一个非常基本的水平.还有一些其他功能正在开发中，但由于没有空闲时间还得等. 尽管如此，Paisely Park在其目前的状态下是功能齐全的，而且非常容易使用。

### 加载

在主窗口中，您将在这里加载标点预设。只需从列表中选择一个标点预设，然后单击“加载”。瞬间，标点就会出现在游戏中。~~这些标点不仅会出现在你的屏幕上，而且也会出现在你的团队其他人的屏幕中。在和你不认识的人一起使用之前，请注意这一点。~~（5.2版本之后该软件仅限于单人使用，优点则为中途可更改的预设）
你也可以利用ACT的尼尼科技插件利用游戏内的宏随时修改标点。

### 创建

要创建一个新的预设，只需将标点放在游戏中希望保存它们的位置。然后，单击Paisley Park里的“创建”并将预设命名成你需要的名字，例如O8s,E8s内DD, E4S，jio神兵等等，然后确保选中“使用当前路标”选项，最后单击“创建”。这将从列表中添加一个新的预设。现在，在主窗口中，您可以从下拉列表中选择这个预设，并随时单击“加载”来加载此预设。

### 编辑

编辑功能与“创建”类似，但它适用于现有的标点预设。不勾选“使用当前路标”，您将只更新预设的名称。

### 删除

删除操作非常简单，只需选择要删除的预设，然后单击“删除”。Paisely Park会首先询问您是否要删除，以确保您不会犯任何不必要的错误。

### 导入/导出

Paisley Park的创建是为了便于在各种场景下设置路标. 考虑到这一点，Paisely Park应该有一个导入和导出预设的功能，以便与其他玩家共享。 只需单击“导入”并粘贴来自另一个用户的JSON字符串，然后单击导入， 就会把相同的标点导入到你的Paisley Park。分享你自己的也可以。只需单击要共享的预设，然后单击“导出”。这将把JSON字符串复制到剪贴板，在那里可以粘贴到QQ基友群、歪歪或其他地方。
同时WaymarkLibrarian-CN也同样支持与Paisley Park 点位互相导入/导出，下载地址：[WaymarkLibrarian](https://github.com/CillinjoLo/WaymarkLibrarian-CN/releases)
### 这里我也提供一个标点合集，也可以联系我增加更多的标点[标点合集](https://docs.qq.com/sheet/DY0ttR2xQT1Vjc2V4)


## 最后

感谢您抽出时间查看此项目。我希望它对你的开荒之夜有用。如果你有任何建议，可以在这个GitHub页面上留下“ISSUE”，或者在Discord上找我，
原作者:LeonBlade#9988
汉化及5.2国服适配：𝑪𝒊𝒍𝒍𝒊𝒏𝒋𝒐𝑳𝒐 "Ewan"#5144
前国服适配：Bluefissure#1957
也可以在Release页面进入加隆德找我

如果你出于任何原因想捐款给原作者Leon，我非常感激。不过，无论是否有金钱上的支持，我们都非常感激。知道人们在使用原作者的工具并享受它们让他很开心。
https://ko-fi.com/leonblade
