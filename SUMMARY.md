# Table of Contents

* ### [Introduction](README.md)
* ### [Deducing Types](chapter1.md)

  * #### [Item 1: Understand template type deduction. ](chapter1/item-1-understand-template-type-deduction.md)
  * #### [Item 2: Understand auto type deduction. ](chapter1/item-2-understand-auto-type-deduction.md)
  * #### [Item 3: Understand decltype. ](chapter1/item-3-understand-decltype.md)
  * #### [Item 4: Know how to view deduced types.](chapter1/item-4-know-how-to-view-deduced-types.md)
* ### [auto](chapter2.md)

  * #### [Item 5: Prefer auto to explicit type declarations. ](chapter2/item-5-prefer-auto-to-explicit-type-declarations.md)
  * #### [Item 6: Use the explicitly typed initializer idiom when auto deduces undesired types.](chapter2/item-6-use-the-explicitly-typed-initializer-idiom-when-auto-deduces-undesired-types.md)
* ### [Moving to Modern C++](chpater3.md)

  * #### [Item 7: Distinguish between \(\) and {} when creating objects. ](chpater3/item-7-distinguish-between-and-when-creating-objects.md)
  * #### [Item 8: Prefer nullptr to 0 and NULL. ](chpater3/item-8-prefer-nullptr-to-0-and-null.md)
  * #### [Item 9: Prefer alias declarations to typedefs.](chpater3/item-9-prefer-alias-declarations-to-typedefs.md)
  * #### [Item 10: Prefer scoped enums to unscoped enums.](chpater3/item-10-prefer-scoped-enums-to-unscoped-enums.md)
  * #### [Item 11: Prefer deleted functions to private undefined ones.](chpater3/item-11-prefer-deleted-functions-to-private-undefined-ones.md)
  * #### [Item 12: Declare overriding functions override.](chpater3/item-12-declare-overriding-functions-override.md)
  * #### [Item 13: Prefer const\_iterators to iterators](chpater3/item-13-prefer-constiterators-to-iterators.md)
  * #### [Item 14: Declare functions noexcept if they won’t emit exceptions.](chpater3/item-14-declare-functions-noexcept-if-they-wont-emit-exceptions-90.md)
  * #### [Item 15: Use constexpr whenever possible.](chpater3/item-15-use-constexpr-whenever-possible.md)
  * #### [Item 16: Make const member functions thread safe. ](chpater3/item-16-make-const-member-functions-thread-safe.md)
  * #### [Item 17: Understand special member function generation](chpater3/item-17-understand-special-member-function-generation.md).
* ### [Smart Pointers](chpater4.md)

  * #### [Item 18: Use std::unique\_ptr for exclusive-ownership resource management.](chpater4/item-18-use-stduniqueptr-for-exclusive-ownership-resource-management.md)
  * #### [Item 19: Use std::shared\_ptr for shared-ownership resource management.](chpater4/item-19-use-stdsharedptr-for-shared-ownership-resource-management.md)
  * #### [Item 20: Use std::weak\_ptr for std::shared\_ptr-like pointers that can dangle. ](chpater4/item-20-use-stdweakptr-for-std-sharedptr-like-pointers-that-can-dangle.md)
  * #### [Item 21: Prefer std::make\_unique and std::make\_shared to direct use of new.](chpater4/item-21-prefer-stdmakeunique-and-std-makeshared-to-direct-use-of-new-139.md)
  * #### [Item 22: When using the Pimpl Idiom, define special member functions inthe implementation file](chpater4/item-22-when-using-the-pimpl-idiom-define-special-member-functions-inthe-implementation-file.md)
* ### [Rvalue References, Move Semantics, and Perfect Forwarding](chpater5.md)

  * #### [Item 23: Understand std::move and std::forward. ](chpater5/item-23-understand-stdmove-and-stdforward.md)
  * #### [Item 24: Distinguish universal references from rvalue references.](chpater5/item-24-distinguish-universal-references-from-rvalue-references.md)
  * #### [Item 25: Use std::move on rvalue references, std::forward on universal references.](chpater5/item-25-use-stdmove-on-rvalue-references-stdforward-on-universal-references.md)
  * #### [Item 26: Avoid overloading on universal references.](chpater5/item-26-avoid-overloading-on-universal-references.md)
  * #### [Item 27: Familiarize yourself with alternatives to overloading on universal references.](chpater5/item-27-familiarize-yourself-with-alternatives-to-overloading-on-universal-references.md)
  * #### [Item 28: Understand reference collapsing.](chpater5/item-28-understand-reference-collapsing.md)
  * #### [Item 29: Assume that move operations are not present, not cheap, and not used.](chpater5/item-29-assume-that-move-operations-are-not-present-not-cheap-and-not-used.md)
  * #### [Item 30: Familiarize yourself with perfect forwarding failure cases.](chpater5/item-30-familiarize-yourself-with-perfect-forwarding-failure-cases.md)
* ### [Lambda Expressions.](chpater6.md)

  * #### [Item 31: Avoid default capture modes.](chpater6/item-31-avoid-default-capture-modes.md)
  * #### [Item 32: Use init capture to move objects into closures.](chpater6/item-32-use-init-capture-to-move-objects-into-closures.md)
  * #### [Item 33: Use decltype on auto&& parameters to std::forward them. ](chpater6/item-33-use-decltype-on-autoandand-parameters-to-stdforward-them.md)
  * #### [Item 34: Prefer lambdas to std::bind. ](chpater6/item-34-prefer-lambdas-to-stdbind.md)
* ### [The Concurrency API](chpater7.md)

  * #### [Item 35: Prefer task-based programming to thread-based](chpater7/item-35-prefer-task-based-programming-to-thread-based.md)
  * #### [Item 36: Specify std::launch::async if asynchronicity is essential. ](chpater7/item-36-specify-stdlaunchasync-if-asynchronicity-is-essential.md)
  * #### [Item 37: Make std::threads unjoinable on all paths](chpater7/item-37-make-stdthreads-unjoinable-on-all-paths.md)
  * #### [Item 38: Be aware of varying thread handle destructor behavior](chpater7/item-38-be-aware-of-varying-thread-handle-destructor-behavior.md)
  * #### [Item 39: Consider void futures for one-shot event communication](chpater7/item-39-consider-void-futures-for-one-shot-event-communication.md)
  * #### [Item 40: Use std::atomic for concurrency, volatile for special memory. ](chpater7/item-40-use-stdatomic-for-concurrency-volatile-for-special-memory.md)
* ### [Tweaks](chpater8.md)

  * #### [Item 41: Consider pass by value for copyable parameters that are cheap tomove and always copied](chpater8/item-41-consider-pass-by-value-for-copyable-parameters-that-are-cheap-tomove-and-always-copied.md).
  * #### [Item 42:Consider emplacement instead of insertion.](chpater8/item-42consider-emplacement-instead-of-insertion.md)



