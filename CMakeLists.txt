cmake_minimum_required(VERSION 3.10)
project(data_structure)

set(CMAKE_CXX_STANDARD 11)

add_executable(data_structure main.cpp linear_table/sequence_table.cpp linear_table.h linear_table/single_list.cpp linear_table/doubly_linked_list.cpp linear_table/circular_linked_list.cpp stack.h stack/sequence_stack.cpp stack/SequenceStack.cpp stack/SequenceStack.h stack/double_end_stack.cpp stack/link_stack.cpp queue/link_queue.cpp queue.h queue/circular_queue.cpp tree/binary_tree.cpp tree.h tree/tree.cpp tree/huffman_tree.cpp graph.h sort.h sort/insert_sort.cpp sort/shell_sort.cpp sort/exchange_sort.cpp sort/select_sort.cpp sort/merge_sort.cpp sort/radix_sort.cpp)