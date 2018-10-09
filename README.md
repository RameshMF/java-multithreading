# java-multithreading

<div dir="ltr" style="text-align: left;" trbidi="on">
<div class="font-family-page">

<div dir="ltr" trbidi="on">
<div style="text-align: left;">
<div class="separator" style="clear: both; text-align: center;">
<a href="https://2.bp.blogspot.com/-usx93qDk6ZY/W7bNdq99h9I/AAAAAAAAEGk/RuFGmwLp1TsW0mkbY8Nta8EvzX_xvFKxwCLcBGAs/s1600/Multithreading-Tutorial.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" data-original-height="288" data-original-width="419" src="https://2.bp.blogspot.com/-usx93qDk6ZY/W7bNdq99h9I/AAAAAAAAEGk/RuFGmwLp1TsW0mkbY8Nta8EvzX_xvFKxwCLcBGAs/s1600/Multithreading-Tutorial.png"></a></div>
<span style="font-family: inherit;">As we know that Multithreading in Java is a very important topic.&nbsp;</span>Multithreading means doing things simultaneously, in parallel. In Java, concurrency is done with threads. Threads are units of code that can be executed at the same time. They are sometimes called lightweight processes, although, in fact, a thread is executed within a process (and every process has, at least, one thread, the main thread).<br>
<br>
<span style="color: red;"><b>The source code examples from this up-to-date tutorial are developed using JDK 8 or later (</b></span><b style="color: red;">Lambda expressions, functional interfaces etc</b><b style="color: red;">) and well tested on our local development environment.</b><br>
<br>
In this tutorial,&nbsp;we will learn low-level APIs that have been part of the Java platform from the very beginning. These APIs are adequate for very basic tasks.&nbsp;<span style="font-family: inherit;">In <a href="http://www.javaguides.net/p/java-concurrency-tutorial.html" target="_blank">Java Concurrency Tutorial</a>, we will learn high-level concurrency features introduced with version 5.0 of the Java platform.&nbsp;</span><span style="font-family: inherit;">Java provides multithreading support with the Thread class and an application can create multiple threads executing concurrently.</span></div>
<h3 style="text-align: left;">
<span style="font-family: inherit;">&gt;&gt;&nbsp;<a href="http://www.javaguides.net/2018/09/how-to-create-and-start-thread-in-java.html" target="_blank">How to Create and Start a Thread in Java</a></span></h3>
<span style="font-family: inherit;">This is the first article of this tutorial, in this article, we will learn<span style="background-color: white; color: #24292e; font-size: 16px;">&nbsp;</span><span style="background-color: white; color: #24292e; font-size: 16px;">how to create and run a thread in a Java application.</span><span style="background-color: white; color: #24292e; font-size: 16px;">&nbsp;Java provides two ways to create a thread programmatically.&nbsp;</span><span style="background-color: white; color: #24292e; font-size: 16px;">Implementing the&nbsp;</span><a href="http://www.javaguides.net/2018/09/runnable-interface-in-java.html" style="background-color: white; font-size: 16px;" target="_blank">Runnable</a><span style="background-color: white; color: #24292e; font-size: 16px;">&nbsp;interface and e</span><span style="background-color: white; color: #24292e; font-size: 16px;">xtending the&nbsp;</span><a href="http://www.javaguides.net/2018/09/thread-class-in-java.html" style="background-color: white; font-size: 16px;" target="_blank">Thread</a><span style="background-color: white; color: #24292e; font-size: 16px;">&nbsp;class.</span></span><br>
<h3 style="text-align: left;">
<span style="font-family: inherit;">&gt;&gt;&nbsp;<a href="http://www.javaguides.net/2018/09/java-thread-sleep-example.html" target="_blank">Java Thread Sleep Example</a></span></h3>
<div>
<span style="font-family: inherit;">In this article, we will learn how to pause the execution of a current thread. Java Thread class provides sleep method, which can be used to pause the execution of a current thread. We will use Thread sleep extensively in future posts, so it’s good to know how it works and is it accurate or not?.</span></div>
<h3 style="text-align: left;">
<span style="font-family: inherit;">&gt;&gt;&nbsp;<a href="http://www.javaguides.net/2018/09/java-thread-join-example.html" target="_blank">Java Thread Join Example</a></span></h3>
<div style="font-size: medium; font-weight: 400;">
<span style="font-family: inherit;">Sometimes we need to wait for other threads to finish it’s execution before we can proceed. We can achieve this using Thread join, learn how it works and when we should use it.</span></div>
<h3 style="text-align: left;">
<span style="font-family: inherit;">&gt;&gt;&nbsp;<a href="http://www.javaguides.net/2018/09/java-thread-set-name-example.html" target="_blank">Java Thread Set Name Example</a></span></h3>
<div>
<span style="font-family: inherit;">In this article, we learn how to name a thread in Java. Thread class provides setName and getName Methods to name a Thread.</span></div>
<h3 style="text-align: left;">
<span style="font-family: inherit;">&gt;&gt;&nbsp;<a href="http://www.javaguides.net/2018/09/java-thread-interrupt-example.html" target="_blank">Java Thread interrupt Example</a></span></h3>
<div>
<span style="font-family: inherit;">In this article, we will learn how to interrupt a running thread.&nbsp;An interrupt is an indication to a thread that it should stop what it is doing and do something else.&nbsp;</span></div>
<h3 style="text-align: left;">
<span style="font-family: inherit;">&gt;&gt;&nbsp;<a href="http://www.javaguides.net/2018/09/java-thread-priority-example.html" target="_blank">Java Thread Priority Example</a></span></h3>
<div>
<span style="font-family: inherit;">In this article, we will learn how to priorities threads in a Java application. Each thread has a priority. Priorities are represented by a number between 1 and 10.</span></div>
<h3 style="text-align: left;">
<span style="font-family: inherit;">&gt;&gt;&nbsp;<a href="http://www.javaguides.net/2018/09/java-thread-isalive-example.html" target="_blank">Java Thread isAlive Example</a></span></h3>
<div>
<span style="font-family: inherit;">In this article, we will learn java.lang.Thread class provides isAlive() method to test if this thread is alive or not. A thread is alive if it has been started and has not yet died.</span></div>
<h3 style="text-align: left;">
<span style="font-family: inherit;">&gt;&gt;&nbsp;<a href="http://www.javaguides.net/2018/09/threadgroup-class-in-java.html" target="_blank">ThreadGroup Class in Java</a></span></h3>
<div>
<span style="font-family: inherit;">In this article, we will learn how to group threads.&nbsp;Java provides a convenient way to group multiple threads in a single object. Java thread group is implemented by <i>java.lang.ThreadGroup</i> class.</span></div>
<h3 style="text-align: left;">
<span style="font-family: inherit;">9.&nbsp;<a href="http://www.javaguides.net/2018/09/thread-class-in-java.html" target="_blank">Thread Class in Java</a></span></h3>
<div>
<span style="font-family: inherit;">In this article, we will learn important methods of Thread class with examples.</span></div>
<h3 style="text-align: left;">
<span style="font-family: inherit;">&gt;&gt;&nbsp;<a href="http://www.javaguides.net/2018/09/runnable-interface-in-java.html" target="_blank">Runnable Interface in Java</a></span></h3>
<div>
<span style="font-family: inherit;">In this article, we will learn how to use Runnable interface with examples.</span></div>
<h3 style="text-align: left;">
<span style="font-family: inherit;">&gt;&gt;&nbsp;<a href="http://www.javaguides.net/2018/09/synchronization-in-multithreading-java.html" target="_blank">Synchronization in Multithreading Java</a></span></h3>
<div>
<div>
<span style="font-family: inherit;">In this article, we will learn how to use synchronization to avoid two types of problems arise when multiple threads try to read and write shared data concurrently - 1. Thread interference errors 2. Memory consistency errors.</span></div>
</div>
<div>
<h3>
<span style="font-family: inherit;">&gt;&gt;&nbsp;<a href="http://www.javaguides.net/2018/09/threadlocal-class-in-java.html" target="_blank">ThreadLocal Class in Java</a></span></h3>
</div>
<div>
<span style="font-family: inherit;">We know that threads share Object’s variables but what if we want to have thread-local variables created at a class level. Java provides ThreadLocal utility class to create thread-local variables. Read more to learn about how we can create ThreadLocal variables in java program.</span><br>
<span style="font-family: inherit;"><br></span> There is a separate&nbsp;<a href="http://www.javaguides.net/p/java-concurrency-tutorial.html" target="_blank">Java Concurrency Tutorial</a>&nbsp;for high-level concurrency features Executor framework introduced with version 5.0 of the Java platform.<br>
<h2 style="text-align: left;">
Executor Framework</h2>
</div>
<div>
<span style="font-family: inherit;">With an Executor framework, we only have to implement the Runnable objects and send them to the executor. The executor is responsible for their execution, instantiation, and running with necessary threads. But it goes beyond that and improves performance using a pool of threads. When you send a task to the executor, it tries to use a pooled thread for the execution of this task, to avoid continuous spawning of threads.</span><br>
<span style="font-family: inherit;"><br></span><span style="font-family: inherit;">Another important advantage of the Executor framework is the Callable interface. It's similar to the Runnable interface, but offers two improvements, which are as follows:</span><br>
<span style="font-family: inherit;">1. The main method of this interface, named call(), may return a result.</span><br>
<span style="font-family: inherit;">2. When you send a Callable object to an executor, you get an object that implements the Future interface. You can use this object to control the status and the result of the Callable object.</span><br>
<h3 style="text-align: left;">
<a href="http://www.javaguides.net/p/java-concurrency-tutorial.html" target="_blank">Java Concurrency Tutorial</a></h3>
<div>
In this tutorial, we will learn following high-level concurrency features Executor framework:</div>
<div>
<div style="text-align: left;">
</div>
<ol style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/09/executorservice-interface-in-java.html" style="font-family: inherit;" target="_blank">ExecutorService Interface in Java</a></li>
<li><a href="http://www.javaguides.net/2018/09/scheduledexecutorservice-interface-in-java.html" style="font-family: inherit;" target="_blank">ScheduledExecutorService Interface in Java</a></li>
<li><a href="http://www.javaguides.net/2018/09/future-interface-in-java.html" style="font-family: inherit;" target="_blank">Future Interface in Java</a></li>
<li><a href="http://www.javaguides.net/2018/09/java-callable-and-future-tutorial.html" style="font-family: inherit;" target="_blank">Java Callable and Future Tutorial</a></li>
<li><a href="http://www.javaguides.net/2018/09/executors-newsinglethreadexecutor-method-example.html" style="font-family: inherit;" target="_blank">Executors newSingleThreadExecutor Method Example</a></li>
<li><a href="http://www.javaguides.net/2018/09/executors-newfixedthreadpool-method-example.html" style="font-family: inherit;" target="_blank">Executors newFixedThreadPool Method Example</a></li>
<li><a href="http://www.javaguides.net/2018/09/executors-newcachedthreadpool-method-example.html" style="font-family: inherit;" target="_blank">Executors newCachedThreadPool Method Example</a></li>
<li><a href="http://www.javaguides.net/2018/09/executors-newscheduledthreadpool-method-example.html" style="font-family: inherit;" target="_blank">Executors newScheduledThreadPool Method Example</a></li>
</ol>
<div>
Read more about high-level concurrency features on&nbsp;<a href="http://www.javaguides.net/p/java-concurrency-tutorial.html" target="_blank">Java Concurrency Tutorial</a><br>
<h3 style="text-align: left;">
Summary of this tutorial</h3>
</div>
</div>
</div>
<ul style="text-align: left;">
<li><span style="font-family: inherit;">At a low level, we can create a thread in two ways, either by implementing <i>Runnable</i> or by subclassing <i>Thread</i> and overriding the <i>run()</i> method.</span></li>
</ul>
<ul style="text-align: left;">
<li><span style="font-family: inherit;">At a high-level, we use <i>Executors</i>, which use thread pools, which in turn use worker threads.</span></li>
</ul>
<ul style="text-align: left;">
<li><span style="font-family: inherit;">One type of thread pool is the fixed thread pool, which has a fixed number of threads running. We can also use single-thread pools.</span></li>
</ul>
<ul style="text-align: left;">
<li><span style="font-family: inherit;"><i>ExecutorService</i> has methods to execute thread pools that either take a <i>Runnable</i> or <i>Callable</i> task. A <i>Callable</i> returns a result and throws a checked exception.</span></li>
</ul>
<ul style="text-align: left;">
<li><span style="font-family: inherit;">The <i>submit()</i> method returns a <i>Future</i> object that represents the result of the task (if the task is a Runnable, null is returned).</span></li>
</ul>
<ul style="text-align: left;">
<li><span style="font-family: inherit;">An executor has to be <i class="gr-progress">shutdown</i> to close the pool thread with either shutdown() (gracefully) or <i>shutdownNow()</i> (forcefully).</span></li>
</ul>
<ul style="text-align: left;">
<li><span style="font-family: inherit;">A deadlock situation occurs when two or more threads are blocked forever, waiting for each other to acquire/release some resource.</span></li>
</ul>
<ul style="text-align: left;">
<li><span style="font-family: inherit;">Starvation happens when a thread is constantly waiting for a lock, never able to take it because other threads with higher priority are continually acquiring it.</span></li>
</ul>
<ul style="text-align: left;">
<li><span style="font-family: inherit;">A livelock is like a deadlock in the sense that two (or more) threads are blocking each other, but in a livelock, each thread tries to resolve the problem on its own (live) instead of just waiting (dead).</span></li>
</ul>
<ul style="text-align: left;">
<li><span style="font-family: inherit;">A race condition is a situation where two threads compete to access or modify the same resource at the same time in a way that causes unexpected results.</span></li>
</ul>
<blockquote class="tr_bq">
Check out top beginners to expert up-to-date <a href="http://www.javaguides.net/p/core-java.html">Core Java Tutorial (100+ Articles)</a></blockquote>
<div>
<br></div>
</div>
</div>
</div>
