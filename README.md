from keras.models import Sequential
from keras.layers import Reshape, Conv2D, MaxPooling2D, Flatten, Dense, Dropout

# Assuming you've loaded and preprocessed your data (X, y)

# Create a Sequential model
model = Sequential()

# Reshape input to (40, 1, 1)
model.add(Reshape((40, 1, 1), input_shape=(40, 1)))

# Convolutional layers
model.add(Conv2D(32, kernel_size=(3, 3), activation='relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))

model.add(Conv2D(64, kernel_size=(3, 3), activation='relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))

# Flatten layer
model.add(Flatten())

# Dense layers
model.add(Dense(128, activation='relu'))
model.add(Dropout(0.2))

model.add(Dense(64, activation='relu'))
model.add(Dropout(0.2))

# Output layer
model.add(Dense(7, activation='softmax'))

# Compile the model
model.compile(loss='categorical_crossentropy', optimizer='adam', metrics=['accuracy'])

# Print model summary
model.summary()
