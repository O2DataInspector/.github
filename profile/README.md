# Data Inspector
Data Inspector is a tool for analysing, debugging and troubleshooting [ALICE O2](https://github.com/AliceO2Group/AliceO2) analyses tasks.
It allows inspecting messages and adjusting workflows in a convenient way through a browser. 
Currently supporting [ROOT](https://root.cern/) and [Apache Arrow](https://arrow.apache.org/) serialization.

It consists of three main parts.

1. [ALICE O2 fork](https://github.com/O2DataInspector/AliceO2/tree/DataInspector), defining services responsible for inspecting messages and communication with devices,
2. [Proxy](https://github.com/O2DataInspector/DataInspector) - REST API layer between running workflow and client,
3. [GUI](https://github.com/O2DataInspector/DataInspectorGUI) - [React](https://reactjs.org/) based web application.