Summary of the Thesis:

Title:Method of Reducing the Solution of Multidimensional Partial Differential Equations to Solving a Series of Related One-Dimensional Problems with Subsequent Coordination of Their Solutions*

Problem Addressed:
The thesis addresses the computational challenge of solving complex systems of multidimensional partial differential equations (PDEs), particularly when such solutions require significant computational resources. These resources often exceed the capabilities of standard personal computers and are typically only available on supercomputers, which are not easily accessible to many researchers.

Solution Proposed
I propose a method to reduce the complexity of solving multidimensional PDEs by decomposing the problem into a series of one-dimensional problems. The solutions of these one-dimensional problems are then coordinated to achieve a solution for the original multidimensional equation. This method leverages gradient-based techniques to optimize the coordination of solutions, using the Python programming language for numerical verification.

The work also involves implementing parallel computing techniques using graphical processing units (GPUs), which have the potential to handle large-scale computations more efficiently than traditional CPUs. By using the CUDA architecture from NVIDIA, I explore the potential of GPUs to solve PDEs in a parallelized manner.

Key Contributions:
1. Gradient-Based Coordination: Development of a gradient method to coordinate the solutions of systems of linear equations derived from one-dimensional problems. This includes deriving formulas for calculating the gradient and optimizing the step size in the gradient method.

2. Numerical Experiments:I conducted numerical experiments to verify the proposed method, demonstrating its effectiveness and potential for further research. The experiments showed rapid convergence, indicating the method's practical applicability.

3. Parallel Computing Implementation: A parallelized approach was tested using a simple example (Laplace's equation) on a two-dimensional domain. The method was also implemented on GPUs, showcasing the advantages of using parallel computing for solving large-scale problems.

4. Memory Efficiency: A modification of the square root method was proposed for solving systems with tridiagonal symmetric matrices, stored in vector form to save memory and avoid unnecessary operations.

Recommendations:
1. Further Research: The thesis recommends further research into the proposed method, particularly its application to more complex and higher-dimensional problems.

2. Optimization of Parallel Algorithms:Continued development and optimization of parallel computing algorithms are suggested to fully exploit the capabilities of GPUs.

3. Practical Applications:The author suggests applying the method to real-world problems in mathematical physics and other fields where large-scale simulations are required.

This thesis demonstrates a promising approach to overcoming the limitations of traditional computational methods for solving PDEs, particularly by harnessing the power of modern GPUs for parallel computation.
