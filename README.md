# Synchronized-vs-Volatile

They can both guarantee the accessibility. but volatile cannot guarantee atom.

For Synchronized:
    1.Before a thread is unlocked, the shared value will be updated to JMM(Java memory model,which describe the describes how threads in the Java programming language interact through memory).
    2.When a thread is locked, the shared value will be cleared in the thread and the shared valued will be read from the JMM.
    3. that must be the same lock.
