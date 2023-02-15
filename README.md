Результат выполнения программы:

20:59:02: Executing ':JvmExperience.main()'...\
 Task :compileJava UP-TO-DATE\
 Task :processResources NO-SOURCE\
 Task :classes UP-TO-DATE\
 Task :JvmExperience.main()\
Please open 'ru.netology.JvmExperience' in VisualVm

20:59:33.631296300: loading io.vertx\
Классы из пакета io.vertx загружены в Metaspace\
20:59:34.086700200: loaded 529 classes\
На данный момент в Metaspace загружено 529 классов, мы можем наблюдать, что график как раз возрос в этот момент (см. точка 1).\
Значение на графике Heap также подросло (см.точка 1)\
20:59:37.090561200: loading io.netty\
Классы из пакета io.netty загружены в Metaspace\
20:59:37.925815800: loaded 2117 classes\
На данный момент загружено уже 2117 классов, мы можем наблюдать дальнейший рост граффика Classes (см.точка 2)\
Значения на графике Heap снизилось, что связано с работой Garbage Collector(см.точка 2), значение на графике Metaspace резко возросло(см. точка 2)\
20:59:40.938755: loading org.springframework\
Классы из пакеты org.springframework загружены в Metaspace\
20:59:41.205827200: loaded 869 classes\
На данный момент загружено уже 869 классов. Мы можем видеть рост на графике Classes (см. точка 3), значение в Metaspase продолжает расти (см. точка 3)\
20:59:44.213448100: now see heap\
Информационное сообщение, обращающее внимание на загрузки в heap\
20:59:44.213636800: creating 5000000 objects\
Сообщение о том, что  в heap создаются 5000000 объектов\
20:59:44.481897700: created\
Сообщение о том, что 5000000 объектов успешно созданы. Мы можем наблюдать на графике Heap рост, связанный с созданием объектов (см. точка 4)\
20:59:47.491516700: creating 5000000 objects\
Сообщение о том, что  в heap создаются 5000000 объектов\
20:59:47.654460400: created\
Сообщение о том, что 5000000 объектов успешно созданы. Мы можем наблюдать на графике Heap рост, связанный с созданием объектов (см. точка 6)\
20:59:50.726085900: creating 5000000 objects\
Сообщение о том, что  в heap создаются 5000000 объектов\
20:59:50.946661100: created\
Сообщение о том, что 5000000 объектов успешно созданы. Мы можем наблюдать на графике Heap рост, связанный с созданием объектов (см. точка 7)\
BUILD SUCCESSFUL in 51s\
Программа завершила свою работы, перед этим мы види рост и резкое падение использоваемого значения Heap (см. точки 7,8),\
при том зараезервированное значение Heap осталось на прежнем уровне, это связано с работой Garbage Collector.\
2 actionable tasks: 1 executed, 1 up-to-date\
20:59:54: Execution finished ':JvmExperience.main()'.

![Metaspace](https://sun9-53.userapi.com/impg/TGmzWsakbW5tjYMRhkC50lmMb5euKZO2EJY_xA/1QM0zaxzH7M.jpg?size=1800x1013&quality=95&sign=b221e4b0e967d2e4dcb3036d64486aed&type=album)
![Heap and Classes](https://sun9-5.userapi.com/impg/AfE89NsHAe0oenzeXF1VYRJhPizSxB19CXk3Fw/7Xzo1V75oI4.jpg?size=1800x1013&quality=95&sign=c0e5e082c0a03583bcf3db94623fc25c&type=album)




