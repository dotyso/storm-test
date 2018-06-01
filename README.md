1. stormHelloWorld项目
  1）使用eclipse本机编译调试运行：直接运行main函数，输出内容在控制台上
  2) 使用mvn ，将排除storm jar包，复制在服务器上，以集群模式运行：
  
  bin/storm jar examples/storm-ys/StormHelloWorld-1.0-SNAPSHOT-jar-with-dependencies.jar com.mycompany.stormhelloworld.ExclamationTopology exclamationTopology 
  
  在 Storm UI上查看
