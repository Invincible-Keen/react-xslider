React-xslider
====

    > slider��һ���ֲ������ʵ����swiper����Ҫ���ܣ��Զ����ţ�����ѭ�����Լ�swiper���߱���������ģʽ��
	
    ## ����
	* ���С��ûѹ����Դ�����13kb
	* ���ܷḻ����ȸ��С���อ��ȫ
	* �����أ�����ƶ���ҳ�����ܵ�����
	* �Զ�����ʽ����ʵ��
	
	--------
	
	##����
    <label>react</label>
    
	--------
	
	##��װ��
    > npm install react-xslider --save
    
    --------

    ##���������� props

    <label>auto:</label> bool,  �Ƿ��Զ�����<br>
    <label>speed:</label> number, �Զ�����ʱ����<br>
    <label>loop:</label> bool, �Ƿ�����ѭ��<br>
    <label>lasy:</label> bool, �Ƿ�������<br>
    <label>paginationHide:</label> bool, �Ƿ����ط�ҳ��<br>
	
    --------

    ###�����demo1
	###�����demo2 auto�Զ�����
	###�����demo3 loop����ѭ��
	###�����demo4 lasy������ģʽ
	
	������ģʽ��������items�ܶ�, ����ͼƬ�����ص��龰</h2>
    dom����Զ��ֻ��̬����3��slider-item��������Ϊitems�ܶർ����������<br>
    ��������ҳ��֮����л�
	
	###�����demo5 paginationHide����ʾ��ҳ��


    ###�Զ����ҳ����ʽ
    ```
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
    ```
