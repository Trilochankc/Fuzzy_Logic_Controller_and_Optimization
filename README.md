# Fuzzy_Logic_Controller_and_Optimization
Overview of Optimization Techniques In this section of the report, we will further dive into comparison of two popular optimization techniques: Particle Swarm Optimization (PSO) and Differential Evolution (DE). Similar to the GA method, both of them helps us find the best solution to optimize a task, like helping to find the quickest route to solving a maze. Unlike, GA which was used in the FLC system, here two CEC'2005 benchmark functions will use used. Further, the mean and stander deviation will be use to evaluate both the optimization techniques in Shifted Sphere Function and Shifted Rastrigin’s Function which are the benchmark functions. Following is a simple definition both the benchmark function:

• F1 (Sphere): This is a simple function which can also be refereed to as unimodal function. The unimodal functions are those that have only one particular solution. Hence, this is used to check how fast the algorithm can solve and find the best possible solution (Suganthan et al. 2005).



• F9 ( Shifted Rastrigin): This problem is much tricky, as a result they are also refereed to as multimodal function. These functions have multiple options where one of them being the best possible situation. This test how well the algorithm can avoid not getting stuck in other solutions to find the best possible solution (Suganthan et al. 2005).




Moreover, the reason for the choice of both this benchmark function is as they both represent different type of challenges. The F1 helps to identify how fast the algorithm can find the best possible solution whereas F9 helps to identify how well the algorithm can tackle with various problems and still find the best possible solution (Tresnadi et al. 2021).

 Experiment Setup and Parameters For the experimental setup, Particle Swarm Optimization (PSO) and Differential Evolution (DE) were used to solve the benchmark function of F1 and F9 explain above. In order for the optimization to solve the problem 30-dimensional space was mentioned, which can be visualized a huge filed that consists of tone of areas to look for the problem, meaning the with 30-dimensional space the area is huge making is more complicated to find the best algorithm. Also, in order for both the algorithm to find the best possible situations 100 iterations has been allocated, to find the best solution. In order to obtain better output, the iteration can be increased but as the iteration is increased the consumption of computational power is also increased. After the 100 tires is completed mean and standard deviation is used to evaluate the optimum algorithm. Further, explain into the evaluation method is mentioned below:

• Mean: This is an average of all the solution found by the algorithms. A lower value is mean refers to better performance as it means that the algorithm found better solutions in an average.

• Standard Deviation: This shows the change between the solution of one try to the another, a lower value refers to higher similarities between the solutions where as a higher value refers to a drastic change in two solutions.

Moreover, by looking at the average and the consistency of the solutions, the evaluation can be done on which algorithm out performed. (Suganthan et al. 2005)

4.3. Performance Analysis and Discussion After running the algorithm, following were the output for both the function:

• F1 (Sphere Function):

Algorithm Mean Standard Deviation (Std)

PSO 7537.611398528888 1655.9970941347706

DE 6.852441419298838e-14 9.583286059978823e-14

From the above, table it is prominent that DE out performed PSO, as the mean and standard deviation for PSO are high suggesting it wasn’t close to the ideal solution and the solutions varied by a drastic measure. Nonetheless, the DE was quite close to the optimum solution as the mean is very close to zero value and likewise the solutions were consistent.

• F9 (Shifted Rastrigin Function):

Algorithm Mean Standard Deviation (Std)

PSO 8243.523835556705 2702.96999554988

DE 99.16390584955525 8.137266574246135

From the above, table DE has once again out performed PSO, as the mean and standard deviation for PSO are high suggesting it wasn’t close to the ideal solution and the solutions varied by a drastic measure. Nonetheless, the DE was quite close to the optimum solution but in comparison to PSO by a huge margin and likewise the solutions were consistent as the Std is lower. 

Final Conclusion Overall, this project demonstrated the implementation of FLC in smart home control system for the disable individuals, alongside optimizing the FLC models with GA optimization technique which had a positive change to the system. Likewise, other optimization techniques such as PSO and DE were also used in two benchmark functions to see evaluate their performance.
