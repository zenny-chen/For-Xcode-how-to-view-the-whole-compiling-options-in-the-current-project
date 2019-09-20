# For-Xcode-how-to-view-the-whole-compiling-options-in-the-current-project
使用Xcode如何查看当前项目工程的所有编译选项

<br />

我们在使用Xcode时往往使用该IDE的Build Settings界面来编辑当前项目工程所需的编译选项。有时为了方便，我们希望能知道当前项目工程用了哪些编译选项，使得这项选项能移植到其它项目或其他类Unix平台上，我们该如何做呢？其实也很简单，只需4步即可完成。

首先，我们在新建好的项目工程中写一句包含语法错误的代码，如下图所示：

![step 1](https://github.com/zenny-chen/For-Xcode-how-to-view-the-whole-compiling-options-in-the-current-project/blob/master/step1.png)

然后，点击左侧导航栏中上部中间那个警探号按钮，如下图所示：

![step 2](https://github.com/zenny-chen/For-Xcode-how-to-view-the-whole-compiling-options-in-the-current-project/blob/master/step2.png)

随后，我们用鼠标右键点击错误信息，然后选择“Reveal In Log”，如下图所示：

![step 3](https://github.com/zenny-chen/For-Xcode-how-to-view-the-whole-compiling-options-in-the-current-project/blob/master/step3.png)

最后，我们就能在中间栏中看到完整的编译选项信息了。我们可以从中挑选对自己有用的部分。下图中红色框出来的部分就是编译选项开始部分，之前的是编译工具的完整路径。

![step 4](https://github.com/zenny-chen/For-Xcode-how-to-view-the-whole-compiling-options-in-the-current-project/blob/master/step4.png)

我们可以选中感兴趣的部分，然后直接复制即可。

