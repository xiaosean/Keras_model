layer - > 0===============
class_name = Dense
units = 100
activation = linear
layer - > 1===============
class_name = Activation
activation = relu
layer - > 2===============
class_name = Dropout
rate = 0.2
layer - > 3===============
class_name = Dense
units = 40
activation = linear
layer - > 4===============
class_name = Activation
activation = relu
layer - > 5===============
class_name = Dropout
rate = 0.2
layer - > 6===============
class_name = Dense
units = 12
activation = linear
layer - > 7===============
class_name = Activation
activation = softmax

train epochs = 300
train batch = 128
test batch = 32
train time = 13139.408946752548
loss = 1.82329849981


accuracy = 0.394857601077