# Documentation

This is how I thing documentation should be in opensource projects. This is the way I'd like to see documentation written in an open source project when I'm trying to use it.

On my first job as a programmer, I have to work with an extint technology called "Lotus Notes". Lotus notes was a documental database that was widelly used back in the early 2000's. It had one of the most friendly documentation systems you can imagine. Every page of the documentation had the following sections:

1. **Name of the function**: Self explanatory
2. **Synopsys**: The signature of the function, with details of the parameters and return values when needed.
3. **Defined**: The header function or package you have to include in order to use it.
4. **Example**: A self contained example. A piece of code that will run if you copy it and paste it in a empty source file. 
5. **Live demo**: A link to a live demo that you can see working. Basically is the above piece of code working in a web browser. This is possible using WebAssembly and the [Emscripten](https://emscripten.org/) build tool.

Check this [example](example.md) to see how the above should look.