# ThreadsSample

Teste feito sem usar Coroutines, para estudo.

Thread:

É uma unidade de execução em um programa.
No contexto do Android, as threads são usadas para realizar operações que não devem bloquear a thread principal (também conhecida como thread principal da UI) para manter a responsividade do aplicativo.
As threads permitem executar tarefas em segundo plano, como acesso à rede, cálculos intensivos ou operações de I/O, sem bloquear a interface do usuário.
Em Kotlin, você pode criar threads usando a classe Thread. No entanto, para desenvolvimento Android moderno, é mais comum usar Kotlin Coroutines, que fornecem uma maneira mais concisa e segura de trabalhar com threads.

--------

Handlers:

Um Handler é uma classe usada no Android para programação assíncrona e comunicação entre threads.
Um Handler permite que você envie mensagens e tarefas assíncronas para a thread de UI (thread principal) a partir de outras threads.
É frequentemente usado com Threads e Runnable para agendar tarefas para serem executadas na thread principal.
Os Handlers são especialmente úteis quando você precisa atualizar a interface do usuário a partir de uma thread de fundo, como após a conclusão de uma operação em segundo plano.
Em Kotlin, você pode criar um Handler usando a classe Handler.
Neste caso usei o próprio textView.post para fazer a tarefa.


------------------------------- // -----------------------------------------

Test done without using Coroutines, for study.

Threads

It is a unit of execution in a program.
In the context of Android, threads are used to perform operations that must not block the main thread (also known as the main UI thread) to maintain the responsiveness of the application.
Threads allow you to perform background tasks, such as network access, intensive calculations, or I/O operations, without blocking the user interface.
In Kotlin, you can create threads using the Thread class. However, for modern Android development, it is more common to use Kotlin Coroutines, which provide a more concise and thread-safe way of working with threads.

--------

Handlers:

A Handler is a class used in Android for asynchronous programming and inter-thread communication.
A Handler allows you to send asynchronous messages and tasks to a UI thread (main thread) from other threads.
It is often used with Threads and Runnable to schedule tasks to run on the main thread.
Handlers are especially useful when you need to update the UI from a background thread, such as after a background operation completes.
In Kotlin, you can create a Handler using the Handler class.
In this case I used textView.post itself to do the task.

------------------------------- // -----------------------------------------
