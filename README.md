<style type="text/css">
	body{
		font-family: "Microsoft Yahei";
		font-size: 16px;
	}
	label{
		display: inline-block;
		padding: 5px 10px;
		background-color: #e5e5e5;
		border-radius: 4px;
		margin-right: 5px;
		margin-bottom: 5px;
	}
</style>
	
<h1>React-xslider</h1>
<hr>
    <p>
        <label>slider��һ���ֲ������ʵ����swiper����Ҫ���ܣ��Զ����ţ�����ѭ�����Լ�swiper���߱���������ģʽ��</label>
    </p>
    <p>
        <b>�ŵ㣺</b>
        <label>���С��ûѹ����Դ�����13kb</label><br>
        <label>���ܷḻ����ȸ��С���อ��ȫ</label><br>
        <label>�����أ�����ƶ���ҳ�����ܵ�����</label><br>
        <label>�Զ�����ʽ����ʵ��</label><br>
    </p>
	<p>
        <b>��װ��</b>
        <label>npm install react-xslider --save</label>
    </p>
    <p>
        <b>������</b>
        <label>react</label><label>react-tap-event-plugin</label>
    </p>
    <hr>
    <br>
    ���������� props <br><br>

    <label>auto:</label> bool,  �Ƿ��Զ�����<br>
    <label>speed:</label> number, �Զ�����ʱ����<br>
    <label>loop:</label> bool, �Ƿ�����ѭ��<br>
    <label>lasy:</label> bool, �Ƿ�������<br>
    <label>paginationHide:</label> bool, �Ƿ����ط�ҳ��<br>
    <br>
    <hr>

    <h2>�����</h2>
    <div id="demo1"></div>
    <br>

    <h2>�Զ�����</h2>
    <div id="demo2"></div>
    <br>

    <h2>loop����ѭ��</h2>
    <div id="demo3"></div>
    <br>

    <h2>������ģʽ��������items�ܶ�, ����ͼƬ�����ص��龰</h2>
    dom����Զ��ֻ��̬����3��slider-item��������Ϊitems�ܶർ����������<br>
    ��������ҳ��֮����л�<br>
    <br>
    <div id="demo4"></div>

    <h2>����ʾ��ҳ��</h2>
    <div id="demo5"></div>

    <h2>�Զ����ҳ����ʽ</h2>
    <div id="demo6">
        <textarea>
    .slider-pagination {
        position: absolute;
        bottom: 5px;
        right: 20px;

        span{
            display: inline-block;
            width: 10px;
            height: 10px;
            border-radius: 100%;
            background-color: #ccc;
            margin-right: 5px;
        }
        span.active{
            background-color: #ff2d4b;
        }
    }
        </textarea>
    </div>
    
    <hr>
    <br>
    ��ϵ��<br><br>
    linxi@iwaimai.baidu.com<br>