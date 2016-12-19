# keras_theano
	
	theano setting and mnist test


# theano gpu setting(ubuntu)

touch `.theanorc` under the home and type the context 

	[global]
	floatX=float32
	device=gpu
	[cuda]
	root=/usr/local/cuda-7.5/bin 


# theano test script

`theano_test.py`

test theano library and using gpu or cpu


# dataset_mnist

[donwload link](https://pan.baidu.com/s/1c7VokQ)


# python script
	
`mnist_cnn_local.py`

add function

	def load_data(path='amazon_mnist.pkl.gz'):

to load local dataset


# running

	nohup python mnist_cnn_local.py>mnist_log.txt 2>&1 &






