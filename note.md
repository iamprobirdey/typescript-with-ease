Benefits:
    1. Typescript is super set of Javascript.
    2. Typescript help to write something using the type, which help on a medium/large level software to have less error.
    3. Using Annotation, it runs the code without having error.


Drawback 
    1. Transpilation: Typescript needs to be compiled to Javascript before running to the browser.Process is called Transpilation.
    2. Dicipline mandatory.



Tutotial
    tsc --init

    tsconfig.json -> created.
    
        rootDir: "/",
        sourceMap: true,
        outDir: "./dist",
        noEmitOnError: true,
        esModuleInterop: true,
        strict: true,
        forceConsistentCasingFileNames: true,
        skipLibCheck: true

    launch.json
     "preLaunchTask": "tsc: build - tsconfig.json",



    