```mermaid
  erDiagram
      math/big_integer.hpp ||--o <algorithm>
      math/big_integer.hpp ||--o <compare>
      math/big_integer.hpp ||--o <concepts>
      math/big_integer.hpp ||--o <cstddef>
      math/big_integer.hpp ||--o <cstdint>
      math/big_integer.hpp ||--o <iterator>
      math/big_integer.hpp ||--o <limits>
      math/big_integer.hpp ||--o <ranges>
      math/big_integer.hpp ||--o <string>
      math/big_integer.hpp ||--o <string_view>
      math/big_integer.hpp ||--o <vector>
      math/big_integer.hpp ||--o concepts/arithmetic.hpp
      concepts/arithmetic.hpp ||--o <type_traits>
      math/big_integer.hpp ||--o exceptions/division_by_zero.hpp
      exceptions/division_by_zero.hpp ||--o <string_view>
      exceptions/division_by_zero.hpp ||--o exceptions/unspecified.hpp
      exceptions/unspecified.hpp ||--o <exception>
      exceptions/unspecified.hpp ||--o <string_view>
      math/big_integer.hpp ||--o exceptions/unrepresentable_value.hpp
      exceptions/unrepresentable_value.hpp ||--o <string_view>
      exceptions/unrepresentable_value.hpp ||--o exceptions/unspecified.hpp
```
