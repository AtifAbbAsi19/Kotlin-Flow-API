# Kotlin-Flow-API


Rx2

observableDataSet()
.subscribe(Scheduler)
.operation(it)
.observeOn(Scheduler)
.subscribe{process(it)}



Kotlin Flow

 dataFlow()
.operation(it)
.flowOn(Dispatcher)
.collect{process(it)}

statements written over flowOn will execute in dispacter 

.collection will return data after operation is completed

flowOn(Dispatcher) //it will execute operation method 
