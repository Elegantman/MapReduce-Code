MapReduceԴ�����(��Ҫ�Ĵ�ģ��,others��ʾ��Ŀ¼�µ�.java�ļ����ܳ�):
1.org.apache.hadoop.mapred(�ɰ�MapReduceAPI):
(1).jobcontrol(job��ҵֱ�ӿ�����)
(2).join:(job��ҵ������ģ���������Ӵ����������)
(3).lib(MapReduce�������Ĺ��߷���)
|----(1).aggregate(�������ݾۺϴ�����ļ�)
|----(2).db(���ݿ��������ļ�)
|----(3).others
(4).pipes(Hadoop MapReduce��C++�ӿڴ���)
(5).tools(�Ͱ�����һ��MRAdmin�ļ�����������connect�������°汾�����޴��ļ�)
(6).others
2.org.apache.hadoop.mapreduce(�°�MapReduceAPI):
(1).example(�������Hadoop��ҵ������)
(2).lib(�°�MapReduce�������Ĺ��߷���):
|----(1).aggregate(�������ݾۺϴ�����ļ�)
|----(2).db(���ݿ��������ļ�)
|----(3).others
(3).security(Hadoop1.0�汾������ӵĹ��ڰ�ȫ����Ĵ���)
|----(1).token(���ڰ�ȫ����token��֤)
|        |----(1).delegation(tokenĿ¼�µĴ���ί��token)
|        |----(2).others
|----(2).others
(4).server(Hadoop����˵Ĺ��ܣ���Ҫ����jobTracker,taskTracker)
|----(1).jobtracker(�������Tracker)
|----(2).tasktracker(����ִ��Tracker)
        |----(1).userlogs(����ִ�е��û���־��¼ģ��)
        |----(2).others
(5).split(������ҵjob�ķָ����)
(6).others
3.org.apache.hadoop.filecache(�ļ����棬�����ļ��ַ�):
(1).DistributedCache.java(��jobָ�����ļ�,��jobִ��ǰ,���зַ���taskִ�еĻ�����)
(2).TaskDistributedCacheManager.java(��Job ID��Job Conf�����ò�����Job�����ļ�·������Job���������񼯺�(��ǰTaskTracker�ڵ�)�Լ�һЩ�û�Ȩ�޵���Ϣ)
(3).TrackerDistributedCacheManager.java(,��������û���������task��cache�ļ�)
4.org.apache.hadoop---mapreduce-default.xml:
��Ŀ¼�µ�MapReduce��Ĭ���ļ�,������ַ�˿ںŵȵ����á�