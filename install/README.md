
### Splunk Distributed Configuration Guide
----------

���÷�ũ �л� ȯ�� ����(indexer cluster, search head cluster��) �� ����ȯ�� ����, ��Ÿ ������ �ٷ�ϴ�.

**Test Env**

----------
�Ƹ����� ���� ȯ���� ����. ����� ������ �׽�Ʈ�� t2.large ��..

hostname |  url | IP
-----|------|---
mon  | ec2-52-78-165-90.ap-northeast-2.compute.amazonaws.com | 52.78.165.90
idx1 | ec2-13-124-122-238.ap-northeast-2.compute.amazonaws.com | 13.124.122.238
idx2 | ec2-user@ec2-13-124-203-80.ap-northeast-2.compute.amazonaws.com | 13.124.203.80
idx3 | ec2-13-124-174-31.ap-northeast-2.compute.amazonaws.com | 13.124.174.31
mgmt | ec2-52-78-191-239.ap-northeast-2.compute.amazonaws.com | 52.78.191.239
sh1 | ec2-13-124-204-37.ap-northeast-2.compute.amazonaws.com | 13.124.204.37
sh2 | |
sh3 | |


�䷯���� �����غ� �����̴�.
mgmt : LM + CM + DS + , DMC