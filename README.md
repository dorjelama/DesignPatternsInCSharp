# DesignPatternsInCSharp

# Strategy Pattern in C#

This repository contains a demonstration of the Strategy Design Pattern in C# (Currently). The Strategy Pattern defines a family of algorithms, encapsulates each one, and makes them interchangeable. This pattern allows the algorithm to vary independently from the clients that use it.

## Structure

The project includes the following classes:

- **Context**: Maintains a reference to a `Strategy` object and delegates the algorithm's implementation to the strategy object.
- **IStrategy**: Defines the interface for different strategies.
- **ConcreteStrategyA**: Implements the algorithm to sort a list in ascending order.
- **ConcreteStrategyB**: Implements the algorithm to sort a list in descending order.

## Usage

To see the Strategy Pattern in action, run the `Program` class. The client code demonstrates how to set different strategies and perform operations based on the chosen strategy.

## Running the Project

1. Clone the repository.
2. Open the project in your preferred C# IDE (e.g., Visual Studio).
3. Run the `Program` class.

## Acknowledgments

- This implementation is based on the conceptual example provided by Refactoring Guru.