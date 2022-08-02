# QuarkNPi `v0.2`

<a href='https://github.com/PiCenter/QuarkNPi'><img src="https://img.shields.io/badge/-GitHub@PiCenter-3A3A3A?style=flat&amp;logo=GitHub&amp;logoColor=white" referrerpolicy="no-referrer" alt="GitHub"></a> <a href='https://oshwhub.com/rgb_yes'><img src="https://img.shields.io/badge/-OSHWHub@RGB_YES-5588ff?style=flat&amp;logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB4AAAAeCAYAAAA7MK6iAAAA2UlEQVRIie1W0RLDIAjD3f7/l9nTro4RCFivvd3y1oomQQXlKoyZV1VZGTZwgLjPoHGEPRqGPXUK/kM8FwiHM6bOmAvGsefGLmy/U/eR41LqJnLKPXJcJbUC7DZ8rWeJbRB1WgsCIDGalCE61XSqV1zS5J17zJCnZ2QH8SwAolJA6EUZ7HQc4k/8+8TdU13uRha3TvVKCV0ilqzTdODtcdTAbbNn4MZax2kDD0R5gAJRWzw1rV5/j/aYdV8ifCO7x6UHnDMPgi0gkYDWG61aQKKKteW+nwsReQHXpy5D9yKlhQAAAABJRU5ErkJggg==&amp;logoColor=white" referrerpolicy="no-referrer" alt="OSHWHub"></a>

`If English translation needed, please let me know.`

基于 树莓派4 Raspberry Pi 4 的布局的 Quark N 底板。核心板为稚晖君的 [Project Quantum](https://github.com/peng-zhihui/Project-Quantum) 项目。

此底板特点：

- 引出更多信号线到GPIO脚
- 核心板原生有RJ45引脚，此底板接出了端子
- 增加了一个USB一分四芯片，实际使用了一分二。四个USB接口为2原生+2HUB
- 板上供电使用了独立的LDO（稚晖君的底板使用核心板上的LDO进行稳压）增大了输入电压和整体功率耐受

注意事项：

- 此版已打样，但测试进度较慢，若有问题也可能不在近期的迭代中解决

![](./v0.2.png)
