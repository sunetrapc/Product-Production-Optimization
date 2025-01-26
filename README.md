# Product Production Optimization

## Overview

Welcome to the **Product Production Optimization** repository! This project focuses on optimizing the production quantities of three products to maximize profit, while adhering to resource constraints in a factory setting. By solving this linear programming problem, we can determine how much of each product should be produced to achieve the highest possible profit.

This optimization model uses the **Gurobi optimizer** to solve the problem efficiently, with constraints such as machine capacity, lathe availability, and grinder usage.

## Problem Overview

You are managing a factory that produces three different products, each with a specific profit margin per unit. However, there are limitations on how much you can produce based on available resources:

1. **Machine constraint**: A limited machine capacity restricts production.
2. **Lathe constraint**: Limited lathe availability constrains the production of Product 1 and Product 2.
3. **Grinder constraint**: A limited grinder can only support a combined total of Product 1 and Product 3 production.

Additionally, the number of units for **Product 3** is fixed at **20 units**.

Your goal is to maximize profit while ensuring that all resources are used optimally and constraints are respected.

## Objective

Maximize the total profit from the production of three products while satisfying all resource constraints.

## 📈 Features

- **Linear Programming**: This optimization model is formulated as a linear programming problem, leveraging **Gurobi** to solve it.
- **Resource Constraints**: Ensure that production adheres to machine, lathe, and grinder limitations.
- **Visualization**: A **matplotlib** bar chart is provided to visualize the optimal production quantities for each product.
- **Optimal Solution**: Get the exact production quantities of each product to maximize the profit.
