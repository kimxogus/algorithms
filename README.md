Scala Data Structures and Algorithms [![Build Status](https://travis-ci.org/kimxogus/algorithms-scala.svg?branch=master)](https://travis-ci.org/kimxogus/algorithms-scala)
=========================================

Minimal and clean example implementations of data structures and algorithms in Scala.  
Forked from [keon/algorithms](https://github.com/keon/algorithms)

## List of Implementations
Checked implementations are written in scala. If not, those are not converted to scala yet.

- [array](src/main/scala/algorithms/array)
    - [x] [circular_counter](src/main/scala/algorithms/array/CircularCounter.scala)
    - [x] [flatten](src/main/scala/algorithms/array/Flatten.scala)
    - [garage](python/array/garage.py)
    - [longest_non_repeat](python/array/longest_non_repeat.py/)
    - [merge_intervals](python/array/merge_intervals.py)
    - [missing_ranges](python/array/missing_ranges.py)
    - [plus_one](python/array/plus_one.py)
    - [rotate_array](python/array/rotate_array.py)
    - [summary_ranges](python/array/summary_ranges.py)
    - [three_sum](python/array/three_sum.py)
    - [two_sum](python/array/two_sum.py)
- [backtrack](python/backtrack)
    - [general_solution.md](python/backtrack/)
    - [anagram](python/backtrack/anagram.py)
    - [array_sum_combinations](python/backtrack/array_sum_combination.py)
    - [combination_sum](python/backtrack/combination_sum.py)
    - [expression_add_operators](python/backtrack/expression_add_operators.py)
    - [factor_combinations](python/backtrack/factor_combinations.py)
    - [generate_abbreviations](python/backtrack/generate_abbreviations.py)
    - [generate_parenthesis](python/backtrack/generate_parenthesis.py)
    - [letter_combination](python/backtrack/letter_combination.py)
    - [palindrome_partitioning](python/backtrack/palindrome_partitioning.py)
    - [pattern_match](python/backtrack/pattern_match.py)
    - [permute](python/backtrack/permute.py)
    - [permute_unique](python/backtrack/permute_unique.py)
    - [subsets](python/backtrack/subsets.py)
    - [subsets_unique](python/backtrack/subsets_unique.py)
- [bfs](python/bfs)
    - [shortest_distance_from_all_buildings](python/bfs/shortest_distance_from_all_buildings.py)
    - [word_ladder](python/bfs/word_ladder.py)
- [bit](python/bit)
    - [count_ones](python/bit/count_ones.py)
    - [power_of_two](python/bit/power_of_two.py)
    - [reverse_bits](python/bit/reverse_bits.py)
    - [single_number2](python/bit/single_number2.py)
    - [single_number](python/bit/single_number.py)
    - [subsets](python/bit/subsets.py)
    - [add_without_operator](python/bit/add_without_operator.py)
- [calculator](python/calculator)
    - [math_parser](python/calculator/math_parser.py)
- [dfs](python/dfs)
    - [all_factors](python/dfs/all_factors.py)
    - [count_islands](python/dfs/count_islands.py)
    - [pacific_atlantic](python/dfs/pacific_atlantic.py)
    - [sudoku_solver](python/dfs/sudoku_solver.py)
    - [walls_and_gates](python/dfs/walls_and_gates.py)
- [dp](python/dp)
    - [buy_sell_stock](python/dp/buy_sell_stock.py)
    - [climbing_stairs](python/dp/climbing_stairs.py)
    - [combination_sum](python/dp/combination_sum.py)
    - [house_robber](python/dp/house_robber.py)
    - [longest_increasing](python/dp/longest_increasing.py)
    - [max_product_subarray](python/dp/max_product_subarray.py)
    - [max_subarray](python/dp/max_subarray.py)
    - [num_decodings](python/dp/num_decodings.py)
    - [regex_matching](python/dp/regex_matching.py)
    - [word_break](python/dp/word_break.py)
- [graph](python/graph)
    - [clone_graph](python/graph/clone_graph.py)
    - [find_path](python/graph/find_path.py)
    - [graph](python/graph/graph.py)
    - [traversal](python/graph/traversal.py)
- [heap](python/heap)
    - [merge_sorted_k_lists](python/heap/merge_sorted_k_lists.py)
    - [skyline](python/heap/skyline.py)
    - [sliding_window_max](python/heap/sliding_window_max.py)
- [linkedlist](python/linkedlist)
    - [add_two_numbers](python/linkedlist/add_two_numbers.py)
    - [copy_random_pointer](python/linkedlist/copy_random_pointer.py)
    - [delete_node](python/linkedlist/delete_node.py)
    - [first_cyclic_node](python/linkedlist/first_cyclic_node.py)
    - [is_cyclic](python/linkedlist/is_cyclic.py)
    - [is_palindrome](python/linkedlist/is_palindrome.py)
    - [kth_to_last](python/linkedlist/kth_to_last.py)
    - [linkedlist](python/linkedlist/linkedlist.py)
    - [remove_duplicates](python/linkedlist/remove_duplicates.py)
    - [reverse](python/linkedlist/reverse.py)
    - [rotate_list](python/linkedlist/rotate_list.py)
    - [swap_in_pairs](python/linkedlist/swap_in_pairs.py)
- [map](python/map)
    - [hashtable](python/map/hashtable.py)
    - [longest_common_subsequence](python/map/longest_common_subsequence.py)
    - [randomized_set](python/map/randomized_set.py)
    - [valid_sudoku](python/map/valid_sudoku.py)
- [math](python/math)
    - [extended_gcd](python/math/extended_gcd.py)
    - [gcd](python/math/gcd.py)
    - [prime_test](python/math/prime_test.py)
    - [primes_sieve_of_eratosthenes](python/math/primes_sieve_of_eratosthenes.py)
    - [generate_strobogrammtic](python/math/generate_strobogrammtic.py)
    - [is_strobogrammatic](python/math/is_strobogrammatic.py)
    - [nth_digit](python/math/nth_digit.py)
    - [rabin_miller](python/math/rabin_miller.py)
    - [rsa](python/math/rsa.py)
    - [sqrt_precision_factor](python/math/sqrt_precision_factor.py)
    - [pythagoras](python/math/pythagoras.py)
- [matrix](python/matrix)
    - [matrix_rotation.txt](python/matrix/matrix_rotation.txt)
    - [bomb_enemy](python/matrix/bomb_enemy.py)
    - [rotate_image](python/matrix/rotate_image.py)
    - [sparse_dot_vector](python/matrix/sparse_dot_vector.py)
    - [sparse_mul](python/matrix/sparse_mul.py)
    - [spiral_traversal](python/matrix/spiral_traversal.py)
- [queue](python/queue)
    - [max_sliding_window](python/queue/max_sliding_window.py)
    - [moving_average](python/queue/moving_average.py)
    - [queue](python/queue/queue.py)
    - [reconstruct_queue](python/queue/reconstruct_queue.py)
    - [zigzagiterator](python/queue/zigzagiterator.py)
- [search](python/search)
    - [binary_search](python/search/binary_search.py)
    - [count_elem](python/search/count_elem.py)
    - [first_occurance](python/search/first_occurance.py)
    - [last_occurance](python/search/last_occurance.py)
- [set](python/set)
    - [randomized_set](python/set/randomized_set.py)
- [sort](python/sort)
    - [insertion_sort](python/sort/insertion_sort.py)
    - [meeting_rooms](python/sort/meeting_rooms.py)
    - [merge_sort](python/sort/merge_sort.py)
    - [quick_sort](python/sort/quick_sort.py)
    - [selection_sort](python/sort/selection_sort.py)
    - [sort_colors](python/sort/sort_colors.py)
    - [topsort](python/sort/topsort.py)
    - [wiggle_sort](python/sort/wiggle_sort.py)
- [stack](python/stack)
    - [longest_abs_path](python/stack/longest_abs_path.py)
    - [simplify_path](python/stack/simplify_path.py)
    - [stack](python/stack/stack.py)
    - [valid_parenthesis](python/stack/valid_parenthesis.py)
- [string](python/string)
    - [add_binary](python/string/add_binary.py)
    - [breaking_bad](python/string/breaking_bad.py)
    - [decode_string](python/string/decode_string.py)
    - [encode_decode](python/string/encode_decode.py)
    - [group_anagrams](python/string/group_anagrams.py)
    - [int_to_roman](python/string/int_to_roman.py)
    - [is_palindrome](python/string/is_palindrome.py)
    - [license_number](python/string/license_number.py)
    - [make_sentence](python/string/make_sentence.py)
    - [multiply_strings](python/string/multiply_strings.py)
    - [one_edit_distance](python/string/one_edit_distance.py)
    - [rabin_karp](python/string/rabin_karp.py)
    - [reverse_string](python/string/reverse_string.py)
    - [reverse_vowel](python/string/reverse_vowel.py)
    - [reverse_words](python/string/reverse_words.py)
    - [roman_to_int](python/string/roman_to_int.py)
    - [word_squares](python/string/word_squares.py)
- [tree](python/tree)
    - [segment-tree](python/tree/Segment_Tree)
        - [segment_tree](python/tree/Segment_Tree/segment_tree.py)
    - [binary_tree_paths](python/tree/binary_tree_paths.py)
    - [bintree2list](python/tree/bintree2list.py)
    - [bst](python/tree/tree/bst)
        - [array2bst](python/tree/bst/array2bst.py)
        - [bst_closest_value](python/tree/bst/bst_closest_value.py)
        - [BSTIterator](python/tree/bst/BSTIterator.py)
        - [delete_node](python/tree/bst/delete_node.py)
        - [is_bst](python/tree/bst/is_bst.py)
        - [kth_smallest](python/tree/bst/kth_smallest.py)
        - [lowest_common_ancestor](python/tree/bst/lowest_common_ancestor.py)
        - [predecessor](python/tree/bst/predecessor.py)
        - [serialize_deserialize](python/tree/bst/serialize_deserialize.py)
        - [successor](python/tree/bst/successor.py)
        - [unique_bst](python/tree/bst/unique_bst.py)
    - [deepest_left](python/tree/deepest_left.py)
    - [invert_tree](python/tree/invert_tree.py)
    - [is_balanced](python/tree/is_balanced.py)
    - [is_subtree](python/tree/is_subtree.py)
    - [is_symmetric](python/tree/is_symmetric.py)
    - [longest_consecutive](python/tree/longest_consecutive.py)
    - [lowest_common_ancestor](python/tree/lowest_common_ancestor.py)
    - [max_height](python/tree/max_height.py)
    - [max_path_sum](python/tree/max_path_sum.py)
    - [min_height](python/tree/min_height.py)
    - [path_sum2](python/tree/path_sum2.py)
    - [path_sum](python/tree/path_sum.py)
    - [pretty_print](python/tree/pretty_print.py)
    - [same_tree](python/tree/same_tree.py)
    - [traversal](python/tree/traversal)
        - [inorder](python/tree/traversal/inorder.py)
        - [level_order](python/tree/traversal/level_order.py)
        - [zigzag](python/tree/traversal/zigzag.py)
    - [tree](python/tree/tree.py)
    - [trie](python/tree/trie)
        - [add_and_search](python/tree/trie/add_and_search.py)
        - [trie](python/tree/trie/trie.py)
- [union-find](python/union-find)
    - [count_islands](python/union-find/count_islands.py)

## List of Designs

- [design](python/design)
    - [alarm_system](python/design/alarm_system.md)
    - [all_o_one_ds](python/design/all_o_one_ds.md)
    - [excel_table](python/design/excel_table.md)
    - [LRUcache](python/design/LRUcache.md)
    - [nearby_drivers](python/design/nearby_drivers.md)
    - [ride_sharing](python/design/ride_sharing.md)
    - [task_runner](python/design/task_runner.md)
    - [twitter_feeds](python/design/twitter_feeds.md)

## How to contribute
Please read [CONTRIBUTING.md](CONTRIBUTING.md)
