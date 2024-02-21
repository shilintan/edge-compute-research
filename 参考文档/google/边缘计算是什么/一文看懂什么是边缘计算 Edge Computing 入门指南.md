# 什么是边缘计算？

更新版 2024年 1月 12日•1 分钟阅读



复制 URL

快速跳转

- [为什么需要边缘计算](https://www.redhat.com/zh/topics/edge-computing/what-is-edge-computing#为什么需要边缘计算)
- [构建企业边缘战略](https://www.redhat.com/zh/topics/edge-computing/what-is-edge-computing#构建企业边缘战略)
- [边缘计算的优势](https://www.redhat.com/zh/topics/edge-computing/what-is-edge-computing#边缘计算的优势)
- [边缘网络的组件](https://www.redhat.com/zh/topics/edge-computing/what-is-edge-computing#边缘网络的组件)
- [边缘、数据分析和 AI/ML](https://www.redhat.com/zh/topics/edge-computing/what-is-edge-computing#边缘、数据分析和-ai/ml)
- [边缘计算与电信领域](https://www.redhat.com/zh/topics/edge-computing/what-is-edge-computing#边缘计算与电信领域)
- [边缘计算与云计算](https://www.redhat.com/zh/topics/edge-computing/what-is-edge-computing#边缘计算与云计算)
- [物联网和边缘设备](https://www.redhat.com/zh/topics/edge-computing/what-is-edge-computing#物联网和边缘设备)
- [边缘计算与雾计算](https://www.redhat.com/zh/topics/edge-computing/what-is-edge-computing#边缘计算与雾计算)
- [面临哪些挑战](https://www.redhat.com/zh/topics/edge-computing/what-is-edge-computing#面临哪些挑战)
- [红帽能提供的帮助](https://www.redhat.com/zh/topics/edge-computing/what-is-edge-computing#红帽能提供的帮助)

## 为什么需要边缘计算？

边缘计算是指在用户或数据源的物理位置或附近进行的计算。通过让计算服务靠近这些位置，用户能够使用更快速可靠的服务，公司则能够享受[混合云](https://www.redhat.com/zh/topics/cloud-computing/what-is-hybrid-cloud)计算带来的灵活性。利用边缘计算，公司能够在许多位置使用和分配公共资源池。

[如何借助红帽企业 Linux 布局边缘计算？](https://www.redhat.com/zh/technologies/linux-platforms/enterprise-linux/edge-computing)

[了解红帽的边缘计算视角](https://www.redhat.com/zh/topics/edge-computing/approach)

## 企业如何将边缘计算与数据中心和公共云结合使用？

作为一种战略，边缘计算会将统一的环境从核心数据中心一直扩展到用户和数据附近的物理位置。通过采用[混合云战略](https://www.redhat.com/zh/blog/edge-open-why-scale-out-computing-doesnt-exist-without-open-hybrid-cloud)，企业可以在自己的数据中心和[公共云](https://www.redhat.com/zh/topics/cloud-computing/what-is-public-cloud)基础架构（如[ Amazon Web Services](https://www.redhat.com/zh/partners/aws)、[Microsoft Azure](https://www.redhat.com/zh/partners/microsoft) 或[ Google Cloud ](https://www.redhat.com/zh/partners/google)）上运行相同的工作负载，同样地，边缘战略则将云环境扩展到更多地方。

如今，边缘计算已广泛用于许多行业，包括[电信](https://www.redhat.com/zh/topics/edge-computing/telecommunications)、[制造](https://www.redhat.com/zh/topics/edge-computing/manufacturing)、运输、公用事业等。同样地，企业实施边缘计算的原因也各不相同。

 

[红帽如何将开源技术拓展到边缘](https://www.redhat.com/zh/products/edge)

 

## 边缘计算应用场景

许多边缘用例都源于在本地实时处理数据的需要，因为某些真实应用场景中，将数据传输到数据中心进行处理会导致不可接受的延迟。

### 制造业

现代化的制造厂就是因为实时数据处理需求而要实施边缘计算的一个例子。在工厂车间，[物联网（IoT）](https://www.redhat.com/zh/topics/internet-of-things/what-is-iot)传感器不断生成稳定的数据流，用于防止故障发生和改善运维。据估计，一个拥有 2000 台设备的现代化工厂[每月可产生 2200 兆字节数据](https://www.ibm.com/thought-leadership/institute-business-value/report/transformation-industrial-products)。在设备附近处理这些海量数据（而不是传输到远程数据中心再处理）速度会更快，成本会更低。但是，设备仍然需要通过一个集中的数据平台进行连接。这样一来，设备就可以接受标准化的软件更新，并共享过滤后的数据，帮助改善其他工厂地点的运维。

### 汽车行业

车联网是边缘计算的另一个常见例子。公共汽车和火车都会配备计算机，以跟踪客流和服务交付。送货员可以通过卡车上配备的技术找到最高效的路线。当使用边缘计算策略进行部署时，车队中的每辆车都运行相同的标准化平台，这使得服务更加可靠，并确保数据能得到统一保护。

更进一步的是自动驾驶车辆，这是边缘计算的另一个例子，其中的关键是在网络连接可能不一致的情况下，如何处理大量实时数据。由于数据量巨大，类似无人驾驶汽车这样的自动驾驶车辆会处理车辆自身的传感器数据，以减少延迟。但这些车辆仍然可以连接到中央位置进行无线软件更新。

### 通信行业

边缘计算也有助于使流行的互联网服务保持快速运行。内容交付网络（CDN）将数据服务器部署在靠近用户的地方，从而使繁忙的网站能快速加载，并支持快速视频流服务。

边缘计算的另一个例子就是我们身边的 [5G](https://www.redhat.com/zh/topics/5g-networks/what-is-5g) 基站。电信服务提供商越来越多地应用[网络功能虚拟化（NFV）](https://www.redhat.com/zh/topics/virtualization/what-is-nfv)来运行网络，即在网络边缘使用在标准硬件上运行的[虚拟机](https://www.redhat.com/zh/topics/virtualization/what-is-virtualization)。这些虚拟机可以取代昂贵的专有设备。边缘计算策略使提供商能在数以万计的远程地点保持软件的稳定运行，同时严守统一的安全标准。在移动网络中，应用靠近终端用户运行还可以减少延迟，有助于供应商提供新服务。

[边缘计算的应用场景：太空](https://www.redhat.com/zh/resources/edge-computing-in-space-brief)

![Chinese Webinar Edge Computing](./一文看懂什么是边缘计算 Edge Computing 入门指南.assets/ZH_Webinar_Edge_Computing.jpeg)

#### 从中心到边缘，解读火热的边缘计算

红帽企业开源讲堂：解读边缘计算的应用场景，关键技术，以及红帽如何助力客户构建边缘计算解决方案。

[观看回放](https://app.ma.scrmtech.com/meetings-api/sapIndex/SapSourceData?pf_uid=17113_1759&sid=63538&source=2&pf_type=3&channel_id=22985&channel_name=SEO&tag_id=c5e537770acc07dc%3Fintcmp%3D7013a00000384p6AAA)

## 边缘计算的优势是什么？

边缘计算意味着能以较低的成本提供更快、更稳定的服务。对于用户而言，边缘计算可以带来更快、更一致的体验。对于企业和服务提供商而言，边缘计算能够实现具有实时监控功能的低延迟、高可用性应用。

边缘计算可以降低网络成本、避免带宽限制、减少传输延迟、限制服务故障，并对敏感数据的传输提供更好的控制。加载时间得到了缩短，部署在用户附近的在线服务能同时支持动态和静态缓存功能。

边缘计算所带来的较少的响应时间，使得增强现实和虚拟现实等应用更便于施展拳脚。

边缘计算能带来的其他优势还包括：能够进行现场[大数据](https://www.redhat.com/zh/topics/big-data)分析和聚合，进而实现近乎实时的决策制定。边缘计算可以在本地实现上述所有计算能力，使企业能够执行[安全](https://www.redhat.com/zh/topics/security)实践或满足监管政策的要求，从而进一步降低泄露敏感数据的风险。

边缘计算还能带给企业客户更多弹性并节省成本。通过在本地实现计算能力，即使某些原因导致核心站点停止运行，区域站点仍能独立于核心站点继续工作。让计算处理能力更接近数据源，还可以大幅降低在核心和区域站点之间来回传输数据时所用带宽的成本。

边缘平台可以帮助实现运维和[应用开发](https://www.redhat.com/zh/topics/cloud-native-apps)的一致性。边缘平台应支持互操作性，以便容纳更多硬件和软件环境组合，而非数据中心。有效的边缘战略还允许来自多个供应商的产品在开放的生态系统中协同工作。

[边缘自动化：七个行业用户和示例](https://www.redhat.com/zh/engage/e-book-automation-edge)

## 边缘网络都有哪些组件？

边缘计算可以视为从代码数据中心向外辐射的一系列圆圈。每个圆圈代表向远端边缘移动的不同层级。

- **供应商/企业核心：**这些是传统的"非边缘"层，由公共云提供商、电信服务提供商或大型企业所有并运营。
- **服务提供商边缘：**这些层级位于核心或区域数据中心与最后一英里接入网之间，通常由电信公司或互联网服务提供商所有并运营，服务提供商通过它们为多个客户提供服务。
- **终端用户本地边缘：**这些层级是最后一英里接入网的终端用户侧的边缘层，包括企业边缘（如零售店、工厂、火车）或消费者边缘（如住宅、汽车）。
- **设备边缘：**通过非互联网协议直接连接传感器/执行器的单机（非集群）系统。它代表了网络的远端边缘。

[构建现代边缘基础架构的首要考虑因素](https://www.redhat.com/zh/resources/top-consideration-build-modern-edge-infrastructure-ebook)

## 边缘计算、数据分析和 AI/ML

边缘计算强调数据收集和实时计算，有利于推动数据密集型智能应用的成功。举例来说，[人工智能](https://www.redhat.com/zh/topics/edge-computing/what-is-edge-ai)/[机器学习](https://www.redhat.com/zh/partners/machine-learning-software)（AI/ML）任务，如图像识别算法，在靠近数据源的地方能更有效地运行，无需将大量数据传输到集中的数据中心。

这些应用采取许多数据点的组合，并利用这些数据点推断出更高价值的信息，以帮助企业做出更优决策。这种功能可以改善多种业务互动，如客户体验、预防性维护、预防欺诈、临床决策等。

通过将每个传入的数据点视为[事件](https://www.redhat.com/zh/topics/integration/what-is-event-driven-architecture)，企业可以应用决策管理和 AI/ML 推理技术来过滤、处理、限定和组合事件，以推导出高阶信息。

数据密集型应用可以被分解成一系列阶段，每个阶段在 IT 环境的不同部分执行。边缘在数据获取阶段（即数据收集、预处理和传输时）开始发挥作用。然后，数据经过工程和分析阶段（通常在公共云或[私有云](https://www.redhat.com/zh/topics/cloud-computing/what-is-private-cloud)环境中）进行存储和转换，再用于机器学习模型训练。之后数据再回到边缘的运行时推理阶段，此时就能够供应和监控这些机器学习模型。

我们需要灵活、适应性强、有弹性的基础架构和应用开发平台来满足这些不同的需求，并提供各个阶段之间的连接。

混合云方法在公有云和私有云之间提供了一致的体验，使我们能够灵活地优化部署环境边缘的数据采集和智能推理工作负载、跨[云环境](https://www.redhat.com/zh/topics/cloud)的资源密集型数据处理和训练工作负载，以及接近业务用户的业务事件和洞察管理系统。

边缘计算是混合云大计中的一个重要组成部分，能为您带来一致的应用和运维体验。

[使用新的边缘应用交付交互式媒体](https://www.redhat.com/zh/resources/acg-telco-interactive-media-edge-applications-analyst-material)

## 边缘计算在电信行业的应用

很多电信服务提供商将工作负载和服务向网络边缘转移，因此，采用边缘计算就成了他们的优先重点。

在为高需求的网络应用（如语音和视频通话）提供服务时，即使是毫秒时间也尤为重要。由于边缘计算可以大幅减小延迟对应用的影响，因而服务提供商可以提供新的应用和服务来改善现有应用，特别是 5G 发展后的应用体验。

但这不仅是提供新服务的问题。供应商正转向边缘战略，以简化网络运维，提高灵活性、可用性、效率、可靠性和可扩展性。

### 什么是 NFV？

网络功能虚拟化（NFV）是将 IT 虚拟化运用到网络功能用例中的一种策略。NFV 允许将标准服务器用于过去需要使用昂贵专有硬件才能运行的功能。 

[深入了解 NFV](https://www.redhat.com/zh/topics/virtualization/what-is-nfv)

### 什么是 vRAN？

无线接入网络（RAN）是终端用户设备与运营商网络其他部分之间的连接点。正如网络功能可以被虚拟化一样，RAN 也可以被虚拟化，从而产生虚拟无线接入网络，即 vRAN。

5G 网络的持续推广往往依赖于 vRAN，将 vRAN 作为简化操作、服务更多设备、满足更苛刻应用需求的一条途径。

[通过 vRAN 加快 5G 策略的发展](https://www.redhat.com/zh/blog/accelerate-your-5g-strategy-virtualized-ran-vran)

### 什么是移动边缘计算 MEC?

[MEC](https://www.redhat.com/zh/topics/edge-computing/what-is-multi-access-edge-computing) 也称多接入边缘计算，是服务提供商在移动网络边缘、靠近用户移动设备处为客户提供应用服务环境的一种手段。

MEC 的优点包括增加吞吐量和减少延迟。MEC 将连接点提供给应用开发人员和内容提供商，使他们也能访问更底层的网络功能和信息处理。

[阅读更多关于电信领域边缘计算的内容](https://www.redhat.com/zh/topics/edge-computing/telecommunications)

## 边缘计算与云计算的联系与区别

[云计算](https://www.redhat.com/zh/topics/cloud)是指在云中运行工作负载，而云是一种能够抽象、汇集和共享整个网络中的可扩展资源的 IT 环境。 

传统上，云计算侧重于将集中云服务应用到少量大型数据中心。集中化能够提高资源的可扩展性和共享效率，并保持控制和[企业安全性](https://www.redhat.com/zh/topics/security)。

因为网络需求或其他限制因素，云计算集中化方案常会无法充分处理某些用例，但边缘计算却能应对自如。

此外，如果云战略中包括了在[容器](https://www.redhat.com/zh/topics/containers/whats-a-linux-container)中运行软件，也能与边缘计算模式互补互利。容器使应用具有可移植性，方便企业在适合的地方运行应用。[容器化战略](https://www.redhat.com/zh/topics/containers)可允许企业将应用从数据中心转移到边缘，或从边缘转移到数据中心，而且对运维的影响非常小。

[在分布式混合云中启用边缘交付](https://www.redhat.com/zh/resources/acg-first-edge-distributed-hybrid-cloud-analyst-material)

## 物联网 IoT 和边缘设备

### 什么是物联网 （IoT）?

物联网（IoT）是指将日常物理对象连接到互联网的过程；从灯泡等常见家用物品，到医疗设备等医疗资产，再到可穿戴设备、智能设备甚至智能城市，都可以连接到互联网。

物联网设备不一定是边缘设备。但这些联网设备是许多企业的边缘战略的一部分。边缘计算可以将更多计算能力带到物联网边缘，从而降低物联网设备与中央 IT 网络之间的通信延迟。

设备能够收发数据，就是物联网的标志。但是，边缘计算带来了更现代的方法，让设备与物联网应用一起发送、接收和分析数据。

### 什么是工业物联网 （IIoT）？

[工业物联网（IIoT）](https://www.redhat.com/zh/topics/internet-of-things/what-is-iiot)是物联网的一个类似的概念，是指连接到互联网的工业设备，例如制造厂、农业设施或供应链所使用的机械。

[深入了解什么是物联网（IoT）](https://www.redhat.com/zh/topics/internet-of-things/what-is-iot)

## 雾计算与边缘计算的区别是什么？

雾计算是指在更接近用户和数据源的分布式物理地点进行的计算。 

雾计算是边缘计算的同义词。雾计算和边缘计算之间除字面表述外没有任何区别。

## 边缘计算面临哪些挑战？

边缘计算可以简化分布式 IT 环境，但边缘基础架构并不总是易于实施和管理。

- 相较于向单个核心数据中心添加同等容量，将边缘服务器横向扩展到很多小型站点的做法可能更为复杂。对于小型企业来说，物理位置的管理费用能会让人吃不消。
- 边缘计算站点通常都位于远程，只掌握有限的（甚至没有任何）现场技术专业知识。为了应对现场故障，您需要部署的基础架构，应能够由本地非技术型人员轻松修复，并且可由任意位置的少量专业人员进一步进行集中管理。
- 站点管理操作必须能在所有边缘计算站点中重复执行，以简化管理，更易进行故障排除。如果软件在每个站点的实施方式略有不同，就会出现挑战。
- 边缘站点的物理安全防护往往比核心站点弱得多。边缘战略必须考虑到恶意或意外情况带来的更高风险。

由于数据源和[数据存储](https://www.redhat.com/zh/topics/data-storage)分散在许多地方，企业需要一个能够跨整个 IT 基础架构（包括边缘站点）的共同水平基础架构。即使对于那些已经习惯了跨多个地理位置运维的企业，边缘计算也会带来独特的基础架构难题。企业需要的边缘计算解决方案应满足以下条件：

- 可以使用与企业的集中式基础架构相同的工具和流程进行管理。这包括要在仅有少量（甚至没有）IT 人员的情况下，自动部署、管理和编排数以百计、甚至数以万计的站点。 
- 满足不同边缘层的不同要求，包括硬件占用空间、环境的挑战和成本。
- 提供灵活性来使用由虚拟机、容器和裸机节点组成的混合工作负载，在上面统一运行网络功能、视频流、游戏、AI/ML 以及关键业务应用。
- 确保边缘站点在出现网络故障的情况下继续运行。 
- 可与来自不同供应商的组件进行互操作。单个供应商无法提供端到端的解决方案。