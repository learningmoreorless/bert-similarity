任务： query与bidword的语义相似性

数据： 见data文件夹
      data_1 与 data_2为原始数据，打分说明见“相关性-标注query-bidword.pdf”

      q2b_train /q2b_dev /q2b_test 为模型所用的数据集(根据原始数据得到)，主要根据打分分成两类，分数越高认为越相似，标注为1，否者标注为0

模型：  Bert (chinese_L-12_H-768_A-12) -开源的中文预训练模型
        主要模块为modeling， optimization， tokenization
