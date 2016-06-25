# WheelView

ʵ��ת�ֵ�ѡ���ܣ�Ч������ͼ:

![Ч��ͼ](https://raw.githubusercontent.com/l465659833/WheelView/master/art/sample.gif)

����Ŀ����[�����Ŀ](https://github.com/helloJp/WheelView)�޸Ķ��ɣ����������ĸĶ�ʵ��̫���ˣ������ϳ���ԭ���Ĵ��������⣬�ڲ���ʵ���߼�ȫ�����˴����޸ģ�����������һ����Ŀ���������лԭ���߸��ҵ�������

��˵˵���������Ż��͸��ưɣ�

1. ������������˳����
2. ���Ե��ʵ�ֵ�����������
3. ���������д�������ֹͣ������
4. �����ľ�����������ٶȳ����ȣ��ͻ�����ʱ��ɷ��ȣ�


������������[ԭ��Ŀ](https://github.com/helloJp/WheelView)���Ͼ������붼copy�ˣ���Щϸ��Ҳ�����ں���

# Attributes


| attr ����          | description ���� |
|:---				 |:---|
| lineColor  	     | divider line color �ָ�����ɫ |
| lineHeight  	     | divider line height �ָ��߸߶� |
| itemNumber	 	 | wheelview show item count ��wheelView��ʾitem�ĸ��� |
| noEmpty 			 | if set true select area can't be null(empty),or could be empty ����true��ѡ�в���Ϊ�գ���������ǿ� |
| normalTextColor 	 | unSelected Text color δѡ���ı���ɫ |
| normalTextSize 	 | unSelected Text size δѡ���ı������С |
| selectedTextColor | selected Text color ѡ���ı���ɫ |
| selectedTextSize 	 | selected Text size ѡ���ı������С |
| unitHeight 		 | item unit height ÿ��item��Ԫ�ĸ߶� |

#Method
###1. setData(ArrayList<String> data)
set WheelView data</br> 
����WheelView������

###2. refreshData(ArrayList<String> data) 
**refresh** WheelView data ,and draw again</br>
**ˢ��** WheelView�����ݣ����ػ�

###3. int getSelected()
get selected item index</br>
��ȡѡ�����index

###4. String getSelectedText()
get selected item text</br>
��ȡѡ������ı���Ϣ

###5. boolean isScrolling
is WheelView is scrolling</br>
��ȡWheelView�Ƿ��ڹ�����

###6. boolean isEnable()
is WheelView is enable</br>
��ȡwheelView�Ƿ����

###7. void setEnable(boolean isEnable)  
set WheelView enable</br>
����WheelView�Ƿ����

###8. void setDefault(int index)
set **default selected index**</br>
����**Ĭ��ѡ�����index**
 
###9. int getListSize() 
get WheelView item count</br>
��ȡWheelView��item�����

###10. String getItemText(int index)
get the text by index </br>
��ȡindexλ���ϵ��ı�����

###11. void setOnSelectListener(OnSelectListener onSelectListener)
set listener on WheelView that can get info when WheelView is **scrolling** or **stop scroll**.</br>
��WheelView**���ü���**���� **��������** ���� **����ֹͣ** ����������Ϣ��

###12. void setItemNumber(int itemNumber)
set the number ofitem show in WheelView</br>
����WheelViewչʾ����Ŀ����

###13. int getItemNumber()
get the number ofitem show in WheelView</br>
��ȡWheelViewչʾ����Ŀ����