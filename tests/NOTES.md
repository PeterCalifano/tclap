# Some notes on building in Ubuntu 24.04

- It seems that test30.cpp is not able to compile due to `std::pair` being used with `operator>>`, which does not have any overload. Makefiles and CmakeLists must be modified to fix compilation issues.
- Test 91 is failing. Reason not investigated.
