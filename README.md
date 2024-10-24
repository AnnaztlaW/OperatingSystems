# OperatingSystems
Code within repository is for Kent State course titled operating systems coding project one. This project attempts to implement the producer consumer relationship in the shared memory utilizing a buffer. The producer generates items and puts items onto the table. <b/>
The consumer will pick up items. The table can only hold two items at the same time. When the table is complete, the producer will wait. <b/>
When there are no items, the consumer will wait<b/> 
Semaphores are used to synchronize producer and consumer.<b/>
Mutual exclusion is considered. <b/>
We use threads in the producer program and consumer program. <b/>
Shared memory is used for the “table”.<b/>

There are two programs one for the producer and one for the consumer.<b/>

```bash
$ gcc producer.c -pthread -lrt -o producer
$ gcc consumer.c -pthread -lrt -o consumer
$ ./producer & ./consumer &
```

