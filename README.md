# class-exercise-4-runzhaoli
Modify 'Pima Indians onset of diabetes' by changing the model design by adding/modifying the layer(s) to 

model.add(Dense(24, input_dim=8, activation='relu'))
model.add(Dense(16, activation='relu'))
model.add(Dense(8, activation='relu'))
model.add(Dense(1, activation='sigmoid'))

The accuracy increased to 80.47%
