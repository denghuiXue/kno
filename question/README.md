# 🎉 日常问题

<img src="https://img.shields.io/github/forks/bytesfly/blog" data-origin="https://img.shields.io/github/forks/bytesfly/blog" alt="">
<img src="https://img.shields.io/github/license/bytesfly/blog" data-origin="https://img.shields.io/github/license/bytesfly/blog" alt="">

<style>
/* 三级标题样式 */
h3 {
    margin: 40px 0 20px;
    padding-left: 15px;
    font-size: 1.5em;
    position: relative;
    color: #2196F3;
    display: flex;
    align-items: center;
}

h3::before {
    content: "";
    position: absolute;
    left: 0;
    width: 4px;
    height: 100%;
    background: linear-gradient(180deg, #2196F3, #00BCD4);
    border-radius: 2px;
}

/* 动态分割线 */
.divider {
    height: 3px;
    background: linear-gradient(90deg, 
        rgba(33, 150, 243, 0) 0%,
        rgba(33, 150, 243, 0.8) 50%,
        rgba(33, 150, 243, 0) 100%);
    margin: 30px 0;
    position: relative;
    overflow: hidden;
}

.divider::after {
    content: "";
    position: absolute;
    top: 0;
    left: -100%;
    width: 100%;
    height: 100%;
    background: linear-gradient(90deg,
        rgba(255, 255, 255, 0) 0%,
        rgba(255, 255, 255, 0.4) 50%,
        rgba(255, 255, 255, 0) 100%);
    animation: shine 3s infinite;
}

@keyframes shine {
    to {
        left: 100%;
    }
}

/* 文档内容容器 */
.content-section {
    background: rgba(255, 255, 255, 0.05);
    border-radius: 10px;
    padding: 20px;
    margin: 20px 0;
    border: 1px solid rgba(33, 150, 243, 0.1);
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
    transition: all 0.3s ease;
}

.content-section:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 25px rgba(33, 150, 243, 0.1);
}
</style>

### &emsp;📚 01 为什么点击 ISC 账号登录是白屏

<div class="content-section">
当用户尝试通过 ISC 账号登录小喔设计器时，出现白屏现象。这主要是因为用户的电脑对小喔设计器的登录方式进行了拦截。这种拦截可能是由于电脑的安全设置、防火墙配置或者其他相关的系统限制所导致的。为了解决这个问题，用户可以选择使用离线登录的方式，并进行相应的授权操作，从而能够正常使用设计器。
</div>

<div class="divider"></div>

### &emsp;🔔 02 如何下载授权

<div class="content-section">
小喔 RPA 设计器的下载获取途径为：https://docs.qq.com/doc/DV1ZQb09PdGV5SU1j。在成功下载设计器后，还需要进行授权操作。授权的链接是https://wxamp.woky.info/mp/license/?code=081F3Cll2pLoQe4gSZol2Vp2XT3F3Clw&state=123。用户需要在浏览器中打开授权链接，按照页面提示进行相关操作。
</div>
<div class="divider"></div>

### &emsp;⏰03 如何设置定时执行
<div class="content-section">
要实现小喔设计器的定时执行功能，首先需要将小喔设计器进行激活授权，并导出 pwo 文件。这个 pwo 文件是后续定时执行的基础。接着，用户需要下载并安装山西 rpa 工具箱。安装完成后，登录该工具箱并进行激活操作，确保工具箱处于可用状态。然后，把设计器导出的 pwo 文件导入到山西 rpa 工具箱中。在工具箱中，用户可以找到定时任务设置的相关选项，通过设置相应的时间参数，如执行时间、执行周期等，就可以让设计器按照预定的时间自动运行相关项目或流程。这样一来，用户就无需手动启动设计器，提高了工作的效率和自动化程度。
</div>
<div class="divider"></div>

### &emsp;🔑 04 isc 登录和离线授权登录的区别是什么
<div class="content-section">
ISC 登录和离线授权登录是小喔设计器中两种不同的登录方式，它们各有特点。ISC 登录的优势在于可以使用内网门户账号直接进行登录，无需额外的授权操作，这种方式比较方便快捷，能够让用户快速进入设计器界面，开始进行一些简单的查看和配置工作。然而，需要注意的是，通过 ISC 登录的方式，制作完成的程序无法导出 pwo 文件。这对于一些需要将项目进行外部共享或者在其他环境中继续使用的情况来说，可能会带来不便。而离线授权登录则可以解决这个问题，用户通过离线授权后，可以导出 pwo 文件。这样就能够将设计好的项目文件分享给其他需要的人员，在其他电脑或环境中进行进一步的开发、测试或者运行，提高了项目的灵活性和可移植性。
</div>
<div class="divider"></div>

### &emsp;🎯 05 元素定位不到怎么处理
<div class="content-section">
当在使用小喔设计器进行项目开发时，可能会遇到元素定位不到的情况。为了解决这个问题，可以使用 UI 分析器。首先，在 UI 分析器中，对那些可能变化的元素去掉勾选。这是因为有些元素的属性可能会随着页面的刷新或者其他操作而发生变化，如果不取消勾选，可能会导致定位不准确。然后，点击复制目标按钮，获取准确的元素定位信息。最后，将原来不准确的目标替换为新复制的目标。通过这种方式，可以确保设计器能够准确地识别和操作需要的元素，从而保证项目的正常运行，避免因为元素定位错误而导致的功能失效或错误。
</div>
<div class="divider"></div>

### &emsp;👨‍💻 06 如何联系后台人员
<div class="content-section">
如果在使用小喔设计器的过程中遇到任何问题，需要联系后台人员进行答疑解惑。可以联系后台人员小焦，他的联系电话是 13191142883。此外，用户还可以通过扫描下方提供的二维码添加微信，与小焦进行沟通。小焦作为后台支持人员，具备丰富的技术知识和经验，能够及时帮助用户解决各种技术问题，如设计器的故障排除、功能咨询等。用户在联系小焦时，最好详细描述问题的现象、出现的场景以及相关的操作步骤，这样可以让小焦更快地了解问题并提供有效的解决方案。
</div>
<div class="divider"></div>

### &emsp;🌐 07 浏览器无法打开如何解决
<div class="content-section">
如果在使用小喔设计器时遇到浏览器无法打开的问题，可以通过以下两种方法进行解决。第一种方法是安装谷歌浏览器插件。具体步骤如下：首先，点击小喔设计器左下角的设置按钮，在弹出的菜单中找到驱动设置选项。然后，在驱动设置页面中，点击谷歌扩展下面的安装按钮，最后点击确认，即可完成插件的安装。安装完成后，一般情况下浏览器就能够正常打开了。然而，如果上述方法未能解决问题，还可以尝试另一种方法。即打开谷歌浏览器中的扩展程序页面，找到小喔安装路径下的 xiaowo - studio\assistant\chrome_extensions 文件夹，将该文件夹中的 xiaowo.xpi 文件拖入到浏览器的扩展程序页面中，通过这种方式也可以实现插件的安装和浏览器的正常打开，从而确保小喔设计器的相关功能能够正常使用。
</div>
<div class="divider"></div>

### &emsp;⚙️ 08 软件进程无法打开
<div class="content-section">
当遇到软件进程无法打开的情况时，用户需要检查动作组件的路径是否符合规范要求。正确的路径格式需要使用双引号括入，并且路径中的分隔符要使用英文状态下的双斜杠（//）。如果路径格式不正确，可能会导致软件进程无法正常启动。因此，在设置动作组件的路径时，一定要仔细检查和确认，确保路径的准确性和规范性，这样才能保证软件进程能够顺利打开，设计器能够正常运行，避免因为路径问题而产生的各种错误和故障。
</div>
<div class="divider"></div>

### &emsp;📋 09 程序如何移植复用
<div class="content-section">
要实现小喔设计器中程序的移植复用，首先需要打开小喔设计器的场景文件夹。在场景文件夹中，选择打开文件路径方式，这样就可以看到整个场景的文件结构。然后，将整个文件夹进行压缩操作，将压缩后的文件拷贝到另一台电脑的相应场景目录下。在拷贝过程中，要确保目标电脑上的小喔设计器环境与原电脑基本一致，包括相关的依赖库、插件等。这样，在目标电脑上解压并打开该文件夹后，就可以继续使用之前在原电脑上开发的程序，实现程序的移植复用，方便在不同的环境中继续进行项目的开发、测试和运行，提高工作的灵活性和效率。
</div>
<div class="divider"></div>
