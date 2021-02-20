## Input Data
```
from tensorflow.examples.tutorials.mnist import input_data
data = input_data.read_data_sets('data/fashion')
data.train.next_batch(BATCH_SIZE)

data = input_data.read_data_sets('data/fashion', source_url='http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/')

(train_images, train_labels), (test_images, test_labels) = tf.keras.datasets.fashion_mnist.load_data()
```
