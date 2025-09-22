# W55RP20-EVB-Pico board definition for zephyr RTOS

## Usage
Add this repository as a submodule in your git repo (or copy the relevant
files).

In your `CMakeLists.txt`:
```
set(BOARD_ROOT ${CMAKE_CURRENT_LIST_DIR}/zephyr-board-w55rp20_evb_pico)
set(BOARD w55rp20_evb_pico)
```
