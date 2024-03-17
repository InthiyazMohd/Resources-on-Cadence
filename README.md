# Resources-on-Cadence
This is a Flow Cadence contract that defines a `SomeContract` contract with various structs, functions, and resources.

## SomeStruct

### Properties
- `a`: A publicly settable string variable.
- `b`: A publicly readable string variable.
- `c`: A contract-level accessible string variable.
- `d`: A self-level accessible string variable.

### Functions
- `publicFunc()`: A public function that can be called from any context.
- `contractFunc()`: A contract-level accessible function that can only be called by the contract itself.
- `privateFunc()`: A self-level accessible function that can only be called by the struct itself.
- `structFunc()`: A public function that demonstrates an area within the struct.

## SomeResource

### Properties
- `e`: An integer variable.

### Functions
- `resourceFunc()`: A function within the `SomeResource` resource that demonstrates an area within the resource.

## Usage

1. Deploy the `SomeContract` contract to the desired Flow blockchain network.
2. Interact with the contract using your preferred Flow blockchain development tools and libraries.
3. Access the properties and call the functions as needed:
   - Use `testStruct` to access the properties and functions within the `SomeStruct` struct.
   - Use `createSomeResource` to create an instance of `SomeResource` and return it as a resource.
   - Call `questsAreFun` to execute the code in the respective area.

**Note:** This code is written in Flow Cadence, a resource-oriented programming language used for developing smart contracts on the Flow blockchain. Ensure that you have the necessary tools and environment to compile, deploy, and interact with Flow Cadence contracts.
![image](https://github.com/InthiyazMohd/Resources-on-Cadence/assets/163650159/0380ef21-694b-4cbe-b45b-b8e996e78704)
