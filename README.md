# AutoreleasepoolShim

Using a fake autoreleasepool outside Apple platforms.

From the source file:

>This source file is part of the Swift.org open source project
>
>Copyright (c) 2021 Apple Inc. and the Swift project authors
>Licensed under Apache License v2.0 with Runtime Library Exception
>
>See https://swift.org/LICENSE.txt for license information
>
>See https://swift.org/CONTRIBUTORS.txt for Swift project authors
>
>...
>
>A shim for Linux that runs the given block of code.
>
>The existence of this shim allows you the use of auto-release pools to optimize memory footprint on Darwin platforms while maintaining compatibility with Linux where this API is not implemented.

Some platforms were added.
