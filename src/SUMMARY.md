# Summary

* [Introduction](README.md)
   * [The Framework](first_steps/overview.md)
   * [Downloading rizin](first_steps/getting_rizin.md)
   * [Compilation and Portability](first_steps/compilation_portability.md)
   * [Compilation on Windows](first_steps/windows_compilation.md)
   * [Compilation on Android](first_steps/compilation_android.md)
* [First Steps](first_steps/intro.md)
   * [Command-line Flags](first_steps/commandline_flags.md)
   * [Command Format](first_steps/command_format.md)
   * [Expressions](first_steps/expressions.md)
   * [Basic Debugger Session](first_steps/basic_debugger_session.md)
   * [Contributing to rizin](first_steps/contributing.md)
* [Configuration](configuration/intro.md)
   * [Colors](configuration/colors.md)
   * [Configuration Variables](configuration/evars.md)
   * [Files](configuration/files.md)
* [Basic Commands](basic_commands/intro.md)
   * [Seeking](basic_commands/seeking.md)
   * [Block Size](basic_commands/block_size.md)
   * [Sections](basic_commands/sections.md)
   * [Mapping Files](basic_commands/mapping_files.md)
   * [Print Modes](basic_commands/print_modes.md)
   * [Flags](basic_commands/flags.md)
   * [Write](basic_commands/write.md)
   * [Zoom](basic_commands/zoom.md)
   * [Yank/Paste](basic_commands/yank_paste.md)
   * [Comparing Bytes](basic_commands/comparing_bytes.md)
   * [SDB](basic_commands/sdb.md)
   * [Dietline](basic_commands/dietline.md)
* [Visual mode](visual_mode/intro.md)
   * [Visual Disassembly](visual_mode/visual_disassembly.md)
   * [Visual Assembler](visual_mode/visual_assembler.md)
   * [Visual Configuration Editor](visual_mode/visual_configuration_editor.md)
   * [Visual Panels](visual_mode/visual_panels.md)
* [Searching bytes](search_bytes/intro.md)
   * [Basic Searches](search_bytes/basic_searches.md)
   * [Configurating the Search](search_bytes/configurating_the_search.md)
   * [Pattern Search](search_bytes/pattern_search.md)
   * [Automation](search_bytes/automation.md)
   * [Backward Search](search_bytes/backward_search.md)
   * [Search in Assembly](search_bytes/search_in_assembly.md)
   * [Searching for AES Keys](search_bytes/searching_aes_keys.md)
* [Disassembling](disassembling/intro.md)
   * [Adding Metadata](disassembling/adding_metadata.md)
   * [ESIL](disassembling/esil.md)
* [Analysis](analysis/intro.md)
   * [Code Analysis](analysis/code_analysis.md)
   * [Variables](analysis/variables.md)
   * [Types](analysis/types.md)
   * [Calling Conventions](analysis/calling_conventions.md)
   * [Virtual Tables](analysis/vtables.md)
   * [Syscalls](analysis/syscalls.md)
   * [Emulation](analysis/emulation.md)
   * [Symbols information](analysis/symbols.md)
   * [Signatures](signatures/zignatures.md)
   * [Graph commands](analysis/graphs.md)
* [Scripting](scripting/intro.md)
   * [Loops](scripting/loops.md)
   * [Macros](scripting/macros.md)
   * [Rz-pipe](scripting/rz-pipe.md)
* [Debugger](debugger/intro.md)
   * [Getting Started](debugger/getting_started.md)
   * [Migration from ida, GDB or WinDBG](debugger/migration.md)
   * [Registers](debugger/registers.md)
   * [Memory Maps](debugger/memory_maps.md)
   * [Heap](debugger/heap.md)
   * [Files](debugger/files.md)
   * [Reverse Debugging](debugger/revdebug.md)
   * [Windows Messages](debugger/windows_messages.md)
   * [macOS/iOS](debugger/apple.md)
* [Remote Access](debugger/remoting_capabilities.md)
   * [Remote GDB](debugger/remote_gdb.md)
   * [Remote WinDbg](debugger/windbg.md)
* [Command Line Tools](tools/intro.md)
   * [Rz-ax](tools/rz-ax/intro.md)
   * [Rz-find](tools/rz-find/intro.md)
   * [Rz-run](tools/rz-run/intro.md)
   * [Rz-bin](tools/rz-bin/intro.md)
      * [File Identification](tools/rz-bin/file_identification.md)
      * [Entrypoint](tools/rz-bin/entrypoints.md)
      * [Imports](tools/rz-bin/imports.md)
      * [Exports](tools/rz-bin/exports.md)
      * [Symbols (exports)](tools/rz-bin/symbols.md)
      * [Libraries](tools/rz-bin/libraries.md)
      * [Strings](tools/rz-bin/strings.md)
      * [Program Sections](tools/rz-bin/program_sections.md)
   * [Rz-diff](tools/rz-diff/intro.md)
      * [Binary Diffing](tools/rz-diff/binary_diffing.md)
   * [Rz-asm](tools/rz-asm/intro.md)
      * [Assemble](tools/rz-asm/assemble.md)
      * [Disassemble](tools/rz-asm/disassemble.md)
      * [Configuration](tools/rz-asm/config.md)
   * [Rz-gg](tools/rz-gg/rz-gg.md)
      * [Language](tools/rz-gg/lang.md)
   * [Rz-hash](tools/rz-hash/intro.md)
      * [Rz-hash Tool](tools/rz-hash/rz-hash_tool.md)
* [Plugins](plugins/intro.md)
   * [IO plugins](plugins/ioplugins.md)
   * [Asm plugins](plugins/dev-asm.md)
   * [Analysis plugins](plugins/dev-analysis.md)
   * [Bin plugins](plugins/dev-bin.md)
   * [Other plugins](plugins/dev-other.md)
   * [Python plugins](plugins/python.md)
   * [Debugging](plugins/debug.md)
   * [Testing](plugins/testing.md)
   * [Packaging](plugins/rz-pm.md)
* [Crackmes](crackmes/intro.md)
   * [IOLI](crackmes/ioli/intro.md)
       * [IOLI 0x00](crackmes/ioli/ioli_0x00.md)
       * [IOLI 0x01](crackmes/ioli/ioli_0x01.md)
       * [IOLI 0x02](crackmes/ioli/ioli_0x02.md)
       * [IOLI 0x03](crackmes/ioli/ioli_0x03.md)
       * [IOLI 0x04](crackmes/ioli/ioli_0x04.md)
       * [IOLI 0x05](crackmes/ioli/ioli_0x05.md)
       * [IOLI 0x06](crackmes/ioli/ioli_0x06.md)
       * [IOLI 0x07](crackmes/ioli/ioli_0x07.md)
       * [IOLI 0x08](crackmes/ioli/ioli_0x08.md)
       * [IOLI 0x09](crackmes/ioli/ioli_0x09.md)
   * [Avatao R3v3rs3 4](crackmes/avatao/01-reverse4/intro.md)
       * [.rizin](crackmes/avatao/01-reverse4/rizin.md)
       * [.first_steps](crackmes/avatao/01-reverse4/first_steps.md)
       * [.main](crackmes/avatao/01-reverse4/main.md)
       * [.vmloop](crackmes/avatao/01-reverse4/vmloop.md)
       * [.instructionset](crackmes/avatao/01-reverse4/instructionset.md)
       * [.bytecode](crackmes/avatao/01-reverse4/bytecode.md)
       * [.outro](crackmes/avatao/01-reverse4/outro.md)
* [Reference Card](refcard/intro.md)
* [Acknowledgments](credits/credits.md)
