# ColorPicker

ColorPicker��һ��Ϊandroid��Ŀ�ṩ��ȡɫ����Enjoy it  O(��_��)O<br><br>

![img](https://github.com/DingMouRen/ColorPicker/raw/master/imgs/img.gif)<br><br>

# ʹ�÷���

	1.��modle��build.gradle���������
```
	compile 'com.dingmouren.colorpicker:colorpicker:1.0.1'
```
	2.������ʹ��
	
```
	 private boolean supportAlpha;//�Ƿ�֧��͸����
	 /**
       * ����֧��͸���ȵ�ȡɫ��
       * @param context ����Activity
       * @param defauleColor Ĭ�ϵ���ɫ
       * @param isSupportAlpha ��ɫ�Ƿ�֧��͸����
       * @param listener ȡɫ���ļ�����
       */
	   ColorPickerDialog mColorPickerDialog = new ColorPickerDialog(
	   MainActivity.this,
	   getResources().getColor(R.color.colorPrimary),
	   supportAlpha,
	   mOnColorPickerListener
	   ).show();
	 
	 //ȡɫ���ļ�����
	 private OnColorPickerListener mOnColorPickerListener = new OnColorPickerListener() {
        @Override
        public void onColorCancel(ColorPickerDialog dialog) {//ȡ��ѡ�����ɫ

        }

        @Override
        public void onColorChange(ColorPickerDialog dialog, int color) {//ʵʱ������ɫ�仯
            
        }

        @Override
        public void onColorConfirm(ColorPickerDialog dialog, int color) {//ȷ������ɫ
            
        }
    };
```
	3.ע�⣺���ؼ�֧���޸ġ�ȷ���� ��ȡ������ť�ı�����ɫ����������ColorPicker.show()֮��
	  ����setButtonTextColor(int color)���趨��
	
	
	
	
	
	
	
	
	
	
