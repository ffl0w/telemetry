telemetry is a poor man's attempt at making declarative programming a lesser pain in the rear with maintaining codebases.

The main crux of the declarative paradigm is the maintenance aspect, which is due to how strict it is.

While this is preferred, there's no declarative-styled programming language out there that nicely goes about allowing
conformity in layout out structure of data in a script.

telemetry aims to change that.

## Our philosophy

telemetry's philosophy is simple: enable developers to write strictly structured code without the hassle of non-mutability by reflectively introspecting what's given.

"Mutable" by a programmatically defined viewpoint is the way data changes, more specifically its state. When a programming language offers mutability, it's allowing:

- The outcome of data to change
- The type of data to change

... and the data's meaning to change.

While dynamically typed programming languages serve to be an important aspect of writing applications that need flexibility, they often lead to poor structuring. This can also lead over time to unnecessary operations which can rather come to be crude and against other liked ideas, such as being fast. Even if it may mean a few nanoseconds being lost, they're still precious to the developer. This is not necessarily one of the goals we're looking at achieving with telemetry, but an example of how imperative languages that employ dynamic typing begin to sacrifice organized data structures in favor of developers quickly changing things on the fly.

## Our goals

The goals telemetry wishes to achieve can be outlined as the following:

- Act as a hybrid with permeation to data structure without outright violating original meaning.
- Be a means of modeling and designing instructions to be sent as LCFS.
- Give referential transparency in given rules, such as the allowance of modification to existing data structures via. aliasing and typings.
- Concatenatively call upon cells from pointers as reference data to the original data structure.
- Transform the state of data reactively based on permeability.

## Getting started

Looking at getting started with using telemetry? Check out [our page]() to learn more.

(Coming soon.)
