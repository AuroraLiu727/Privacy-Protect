

# LPA-Offload 

```
├── MultiServer            // Multi server scenario
│       └── update_range2                     // Main calculation process
│       └── privacy_leakage_comp                    // Calculate privacy leakage
│       └── obfuscate_location		// Obfuscate location
│       └── choice3                      // Optimal individual selection strategy
│       └── genetic_algorithm                          // Generate the best individual with the greatest fitness
│       └── simulated_annealing                        //  Simulated annealing algorithm
├── SingleServer            // Single server scenario 
│       └── update_range                          // Main calculation function
│       └── generate_probability                    // Calculate the perturbation probability
│       └── Privacy_leakage_comp                        // Calculate privacy leakage
│       └── obfuscate                      // Obfuscate location
├── GA         // Genetic Algorithm
│       └── matuingFuction                       // Mating&mutation function 
│       └── variationFunction                        // Variation function 
├── Parameters         // System Parameters
├── system_initial         // Calculate the cost associated with offloading
│       └── task_allocate                       // Calculate user offloads matrix
│       └── local_consumption                        // Calculate user-side consumption
│       └── server_consumption                    // Calculate server-side consumption
│       └── offloading_cost                   // Calculate the cost of offloading data from the user to the server 
```

<font size='4.5'>Detailed annotations can be found in the source code, and each function is annotated with the descriptions of the parameters and return values.</font>

## 我的备注
论文《Location Privacy-Aware Task Offloading in Mobile Edge Computing》中提出的MEC环境下任务卸载的位置隐私保护框架LPA-Offloading的实现代码

论文链接：
- https://ieeexplore.ieee.org/document/10065551

 
