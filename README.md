## COUNTER CONTRACT

ThE impl_counter contract is a simple counter contract was built with cairo language and unit tested using Starknet Foundry.

The contract has the functionalities of increasing and decreasing the count either by 1 or by a specific value.

## Functions and their signatures

```
  fn get_count(self: @T) -> u256;
  fn increase(ref self: T);
  fn decrease(ref self: T);
  fn increase_by_value(ref self: T, value: u256);
  fn decrease_by_value(ref self: T, value: u256);
```
