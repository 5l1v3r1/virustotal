# VirusTotal Package #
VirusTotal �� ���ϰ� �����ϱ� ���� Python3 ��Ű��.
�Ʒ��� ���� ������ ����Ѵ�.
```
import virustotal
vt = virustotal.connect('MY-APU-KEY', False)
report = vt.scan('MD5-SHA1-SHA256')
print(str(report['scans']))
```

# update log #
2017/06/07 - ���ϰ�θ� �޾� �ؽ������ �߰�
