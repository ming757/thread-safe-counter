# *thread-safe-counter
## Project #2 : Compare between semaphore and Mutex

### - OS environment : Ubuntu 18.04



- Mutex_result

![image](https://user-images.githubusercontent.com/84621391/121811463-76354100-cc9f-11eb-92c6-f0bd6e813b9b.png)

- Semaphore_result

![image](https://user-images.githubusercontent.com/84621391/121811503-8fd68880-cc9f-11eb-9ca3-47e4b1399221.png)

- Conclusion

According to the above result, it can be seen that the semaphore takes much time than the mutex. Originally, semaphore is usually faster than mutex because they have more shared resources. But in this code, we can see that the mutex takes less time than the semaphore because there is just only one resource.
