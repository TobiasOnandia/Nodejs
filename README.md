*CommonJS* 
require module

module.export  = {
    function()
}

const NAME = require(/...)


*Es modules* 
.mjs recomendado

OBLIGATORIO PONER LA EXTENSION
export function
import { function } from  './..ext'


// modules native

const os = require('node:os')


*Async*
const {promisiFy} = require('node:util')

readFile(./arcivo.txt, utf-8, (err,text) => {
    .....
})

// async & await

// funcion autocompletada -- IIFE

; async () => {
    ....
}()


*SINCRONO, ASINCRONO(PROMISE) => rapido++, ASINCRONO SECUENCIAL(ASYNC && AWAIT)*


