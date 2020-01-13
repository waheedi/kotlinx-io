[kotlinx-io](../../index.md) / [kotlinx.io.buffer](../index.md) / [PlatformBufferAllocator](./index.md)

# PlatformBufferAllocator

`object PlatformBufferAllocator : `[`BufferAllocator`](../-buffer-allocator/index.md)

### Functions

| Name | Summary |
|---|---|
| [allocate](allocate.md) | `fun allocate(size: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Buffer`](../-buffer/index.md) |
| [free](free.md) | `fun free(instance: `[`Buffer`](../-buffer/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [borrow](../borrow.md) | Allocates the buffer of the given [size](../borrow.md#kotlinx.io.buffer$borrow(kotlinx.io.buffer.BufferAllocator, kotlin.Int, kotlin.Function1((kotlinx.io.buffer.Buffer, kotlinx.io.buffer.borrow.T)))/size), executes the given [block](../borrow.md#kotlinx.io.buffer$borrow(kotlinx.io.buffer.BufferAllocator, kotlin.Int, kotlin.Function1((kotlinx.io.buffer.Buffer, kotlinx.io.buffer.borrow.T)))/block) function on this buffer and then frees it correctly whether an exception is thrown or not.`fun <T> `[`BufferAllocator`](../-buffer-allocator/index.md)`.borrow(size: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, block: (buffer: `[`Buffer`](../-buffer/index.md)`) -> T): T` |