# Wenjun_MC46509_challenge

**ACM ID: MC46509**

**Student Name: Wenjun Tang**

**Student ID: MC465097**

**Score: Recall@1: 1.24; Recall@5: 3.64; Recall@10: 6.48**

### I use _train.py_ to train the model, _test.py_ to test the model given the test data, and _test_ACM.py_ to generate the ACM result 'answer.txt'

## Here is my settings:

**python train.py --name twj --fp16 --extra_Google --DA --color_jitter --circle --cosface --contrast --loss_merge --share --batchsize 32 --views 3 --erasing_p 0.5 --droprate 0.5 --pool gem --train_all --use_NAS**
