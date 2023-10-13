# Corning AI challenge _ ITEM 3

### 🏴‍☠️ Machine learning을 이용한 편미분 방정식 (PDE)의 해석법 제안

<br/>

💡 Purpose of project:

Partial differential equations (PDEs) are mathematical equations that describe how a physical quantity, such as temperature, pressure, or density changes in space and time. They are widely used in various fields such as physics and engineering to model real-world phenomena. However, solving PDEs can be computationally expensive and challenging, especially for complex systems with multiple variables. (Unfortunately, many of the physical phenomena we are interested in are very difficult to solve numerically.)

Machine learning (ML) methods have recently been proposed as a promising approach for solving PDEs. Physics-informed neural networks (PINNs) have shown great potential in solving PDEs by incorporating prior physical knowledge into the neural network architecture. Another approach is using deep operator network (DeepONet) which is based on the universal approximation theorem. This method enables learning of PDEs corresponding to varying BCs and ICs without retraining the network.


<br/>

🔑 Objectives:

The primary object of this project is applying PINN or DeepONet to solve PDEs in a “specific application domain”, such as fluid dynamics, wave propagation or heat transfer. The evaluation will focus on developing and testing a neural network-based method for solving PDEs and comparing the results with traditional numerical methods to demonstrate the effectiveness and efficiency of the proposed method.

   * Need to select 2- or 3-dimensional problem.
   * Compare the results obtained using the proposed method with those obtained using traditional numerical methods, such as finite difference or finite element method.
   * Need an analysis of the scalability of the proposed method, by testing it on a range of different problem sizes and computational resources.
   * Investigate the role of physical and mathematical constraints in guiding the solution of PDEs, and how these constraints can be incorporated into the neural network architecture to improve its accuracy and efficiency.


<br/>

📖 참고 내용  

✔️ 전통적인 방식의 수치해석 코드는 제공 가능 (문제 선정 전에 문의 필요,  📧moonj5(@)corning.com)

✔️ 간단한 ODE에 대한 base code
