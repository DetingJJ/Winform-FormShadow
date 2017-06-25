# WinForm ͶӰ��� - FormShadow

[\[ENGLISH README]\](https://github.com/NetDimension/Winform-FormShadow)

__FormShadow__ �ܹ����ٵ�Ϊ���WinForm���ڻ��ƴ���ͶӰ����Ȼ��������� __CS_DROPSHADOW__ ��ʽ������ª���ѿ��ķ�ʽ�� 

�乤��ԭ�����������汾��Visual Studio Shell���õ�ͶӰ��ʽ��ͬ��������������ܴ���4��LayeredWindow��������ӰͼƬ������������ͬ���¼���

![Screen Shot](http://www.ohtrip.cn/media/FormShadowDecorator.png)

֮ǰ��GitHub��������һ���������Ĵ���ͶӰ�Ĺ���[winform.DropShadow](https://github.com/wenerme/winform.DropShadow)��
��Ȼʵ����ͶӰ������ͶӰҲ�ܹ���̬���ɣ������м������⣺
- ��Ӱ����Ч���������弫��Э��
- �����������Ū�ɿ��Ըı��С����ʽ����ô����Ӱ�ӵ�ʱ�򿨶ٷǳ�����
- �ƺ��ڴ�й©���ڴ�Խ��Խ��

���˵������������������������⣬���۴��ٶȻ�������Э���ϣ����˾��ö�Ҫ����һ�������������߲�Ҫ����[��Ц]����

����ΪʲôҪ���������������ԣ����˵�����һ����Ŀ[NanUI](https://github.com/NetDimension/NanUI)�Ѿ��þ�û�и��£�֮ǰһֱ����Win7������˵���ڳ��������⣬����֮ǰ��NanUI����Ӱ����ʹ��DWM��ʵ�ֵģ�
���仰˵����Win8/Win8.1������Ϊϵͳԭ���û�д���ͶӰ���Ƚ��ѿ�����Ȼ������ķ���ΪNanUI�ṩ������һ�ֻ�Ӱ�ӵķ���������ʵ��ԭ��� __winform.DropShadow__ �����Ŀһ����Ҳ������Щ���⣬����Ϊ����һ���
NanUI���и�Ư����Ӱ��Ч���������Ŀ�͵�������

# ����
- ΪWinForm���崴��Ư����ͶӰЧ��������֧�� __�__/__�ǻ__ ״̬�����ͶӰ��ɫ��
- ���ٻ�����Ӱ������˸�������١�
- ������������ı��С�����κ����ơ�



# ʹ������
��������Ӿ���ʹ��FormShadow��򵥵����ӣ���ʼ��һ��Decorator��Ϊ���������Ӱ��Ч����Ȼ���������϶���ЩӰ���ܸı������壨Borderless���Ĵ�С��

```C#
public partial class Form1 : Form
{

	protected readonly FormShadowDecorator ShadowDecorator;

	public Form1()
	{
		InitializeComponent();
		ShadowDecorator = new FormShadowDecorator(this);
		//���ô��ڴ�С����
		//Enable resizing form with shadows.
		ShadowDecorator.EnableResize(true);
	}
}
```


# ��ϵ����
���κ����ʻ�ӭ���ҵ�˽��QQ����һ�����ߣ����ڴ�Ҷ�΢�ſ�������QQȺ�������κ��й���.NET�����Ļ��⡣

__2000��QQȺ:__ 241088256

__�ҵ�QQ:__ 19843266

__����԰:__ [http://www.cnblogs.com/linxuanchen/](http://www.cnblogs.com/linxuanchen/)

# ��������

�����ϲ���ҵĹ�������ô��ӭ�����뵽�κ���Ŀ�Ŀ���������

��Ȼ��Ҳ���Էǳ�ֱ���˵���֧������΢��ɨ�������Һȿ��ȣ���

![Screen Shot](http://www.ohtrip.cn/media/BEG.png)

__����˵֮ǰ���Һȿ��ȵ����ѣ�������������۷�����~��__ 

���� Mr.JSON

