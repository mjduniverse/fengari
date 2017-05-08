[![Build Status](https://travis-ci.org/giann/fengari.svg?branch=master)](https://travis-ci.org/giann/fengari) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<p align="center">
    <img src="https://github.com/giann/fengari/raw/master/logo.png" alt="Fengari" width="304" height="304">
</p>

# fengari
🐺 φεγγάρι - The Lua VM written in JS ES6 for Node and the browser

## So far

- [x] Lexing/Parsing
- [x] Parse bytecode
- [x] Opcodes
- [x] Basic types representation:
- [x] Tag Methods
- [ ] Standard library
    - [x] Base lib
    - [x] Coroutine
    - [x] Debug
    - [x] Math
    - [x] String
    - [x] Table
    - [x] utf8
    - [x] os (~~`os.setlocale()`~~)
    - [x] Package
    - [ ] io
        - [x] `file:__tostring()`
        - [x] `file:write()`
        - [x] `io.close()`
        - [x] `io.stderr`
        - [x] `io.stdin`
        - [x] `io.stdout`
        - [x] `io.write()`
        - [ ] `io.flush()`
        - [ ] `io.input()`
        - [ ] `io.lines()`
        - [ ] `io.open()`
        - [ ] `io.output()`
        - [ ] `io.popen()`
        - [ ] `io.read()`
        - [ ] `io.tmpfile()`
        - [ ] `io.type()`
        - [ ] `file:flush()`
        - [ ] `file:lines()`
        - [ ] `file:read()`
        - [ ] `file:read()`
        - [ ] `file:setvbuf()`
        - [ ] `file:__gc()`
- [ ] C API
    - [x] ...
    - [ ] `lua_arith`
    - [ ] `lua_islightuserdata`
    - [ ] `lua_register`
    - [ ] `lua_setallocf`
    - [ ] `lua_tocfunction`
- [ ] Auxiliary library
    - [x] ...
    - [ ] `luaL_addsize`
    - [ ] `luaL_checkoption`
    - [ ] `luaL_checkversion`
    - [ ] `luaL_newlibtable`
    - [ ] `luaL_optnumber`
    - [ ] `luaL_prepbuffer`
    - [ ] `luaL_pushresultsize`
    - [ ] `luaL_ref`
    - [ ] `luaL_unref`
- [ ] Run [Lua test suite](https://github.com/lua/tests)
    - [x] `calls.lua`
    - [x] `constructs.lua` (`_soft`)
    - [x] `locals.lua`
    - [x] `strings.lua`
    - [x] `vararg.lua`
    - [ ] `all.lua`
    - [ ] `api.lua`
    - [ ] `attrib.lua`
    - [ ] `big.lua`
    - [ ] `bitwise.lua`
    - [ ] `checktable.lua`
    - [ ] `closure.lua`
    - [ ] `code.lua`
    - [ ] `coroutine.lua`
    - [ ] `db.lua`
    - [ ] `errors.lua`
    - [ ] `events.lua`
    - [ ] `files.lua`
    - [ ] `gc.lua`
    - [ ] `goto.lua`
    - [ ] `heavy.lua`
    - [ ] `literals.lua`
    - [ ] `main.lua`
    - [ ] `math.lua`
    - [ ] `nextvar.lua`
    - [ ] `pm.lua`
    - [ ] `sort.lua`
    - [ ] `tpack.lua`
    - [ ] `utf8.lua`
    - [ ] `verybig.lua`
- [ ] DOM API binding

## References

- [Source code for Lua 5.3](lua.org/source/5.3/)
- [Lua 5.2 Bytecode and Virtual Machine](http://files.catwell.info/misc/mirror/lua-5.2-bytecode-vm-dirk-laurie/lua52vm.html)
- [Lua 5.3 Bytecode Reference](http://the-ravi-programming-language.readthedocs.io/en/latest/lua_bytecode_reference.html)
- [A No-Frills Introduction to Lua 5.1 VM Instructions](http://luaforge.net/docman/83/98/ANoFrillsIntroToLua51VMInstructions.pdf)
