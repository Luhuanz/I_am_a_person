# gpt_sovitsԭ��ѵ��������

## һ. ����
1. ������
    - ����������¡��1�������ݡ�5-10����ѵ����
    - ������������¡������Ӣ
    - ������δʵ��

## ��. ѵ��������һ��
1. �̳̣�https://www.bilibili.com/video/BV12g4y1m7Uw
2. 4������
   - ������(ѵ������)��runtime\python.exe webui.py :  http://0.0.0.0:9874
   - ����������棺runtime\python.exe" tools/uvr5/webui.py ��http://0.0.0.0:9873
   - ����ʶ����У�Խ��棺runtime\python.exe tools/uvr5/webui.py:  http://0.0.0.0:9873
   - ������棺runtime\python.exe" GPT_SoVITS/inference_webui.py��http://0.0.0.0:9872
3. ʹ������
   1. ѵ����������![](.images/1fe6b2e2.png)
   2. ѵ������Ԥ����![](.images/0b1e08d2.png)
   3. ѵ��������
4 .ģ��Ȩ���ļ�
   - ![](.images/130e94fb.png)

##  ��. ����onnx
.\runtime\python.exe .\GPT_SoVITS\onnx_export.py
![](.images/2f2b4aae.png)
��������ߴ磺
���룺
gpt_sovits(ref_seq, text_seq, ref_bert, text_bert, ref_audio_sr, ssl_content).detach().cpu().numpy()


## ��. Ԥ����