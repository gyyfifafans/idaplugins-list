# A list of IDA Plugins

I'll be organizing the plugins over time. Please submit PRs if you have any other outstanding plugins. I would like to tag each plugin with its corresponding IDA version, but it will take me a long time to test. If you can help there, please do. 

**If a plugin is only a source repo with no description or documentation, I am not adding it.**

# **TODO**
- [ ] Add more plugins
- [ ] Categorize plugins

# Plugins

* [3DSX Loader](https://github.com/0xEBFE/3DSX-IDA-PRO-Loader): IDA PRO Loader for 3DSX files

* [ActionScript 3](https://github.com/KasperskyLab/ActionScript3): An ActionScript 3 processor module and Flash debugger plugin.

* [Adobe Flash disassembler](https://hex-rays.com/contests/2009/SWF/ReadMe.txt): The 2 plugins present in this archive will enable IDA to parse SWF files, load all SWF tags as segments for fast search and retrieval, parse all tags that can potentially contain ActionScript2 code, discover all such code(a dedicated processor module has been written for it) and even name the event functions acording to event handled in it (eg. OnInitialize). [Download](https://hex-rays.com/contests/2009/SWF/swf.zip)

* [alleycat](https://github.com/devttys0/ida/tree/master/plugins/alleycat): 
  *  Finds paths to a given code block inside a function
  *  Finds paths between two or more functions
  *  Generates interactive call graphs
  *  Fully scriptable

* [Amnesia](https://github.com/duo-labs/idapython): Amnesia is an IDAPython module designed to use byte level heuristics to find ARM thumb instructions in undefined bytes in an IDA Pro database. Currently, the heuristics in this module find code in a few different ways. Some instructions identify and define new code by looking for comon byte sequences that correspond to particular ARM opcodes. Other functions in this module define new functions based on sequences of defined instructions.

* [Android Debugging](https://github.com/techbliss/ADB_Helper_QT_Super_version): This version have both support for native arm debugging via usb and sdk ADV manager.

* [Android Scripts Collection](https://github.com/strazzere/android-scripts): Collection of Android reverse engineering scripts that make my life easier

* [APIScout](https://github.com/danielplohmann/apiscout): This project aims at simplifying Windows API import recovery. As input, arbitrary memory dumps for a known environment can be processed (please note: a reference DB has to be built first, using apiscout/db_builder). The output is an ordered list of identified Windows API references with some meta information, and an ApiVector fingerprint. Includes a convenience GUI wrapper for use in IDA.

* [AutoRE](https://github.com/a1ext/auto_re): Auto-renaming plugin with tagging support.

* [BinAuthor](https://github.com/g4hsean/BinAuthor): Match an author to an unknown binary.

* [BinCAT](https://github.com/airbus-seclab/bincat): BinCAT is a static Binary Code Analysis Toolkit, designed to help reverse engineers, directly from IDA.

* [BinClone](https://github.com/BinSigma/BinClone): BinClone: detecting code clones in malware [SERE 2014]

* [BinNavi](https://github.com/google/binnavi): BinNavi is a binary analysis IDE - an environment that allows users to inspect, navigate, edit, and annotate control-flow-graphs of disassembled code, do the same for the callgraph of the executable, collect and combine execution traces, and generally keep track of analysis results among a group of analysts.

* [Bin Sourcerer](https://github.com/BinSigma/BinSourcerer): BinSourcerer (a.k.a RE-Source Online) is an assembly to source code matching framework for binary auditing and malware analysis.

* [Bootroom Analysis Library](https://github.com/digitalbond/IBAL): IBAL is the IDA Pro Bootrom Analysis Library, which contains a number of useful functions for analyzing embedded ROMs.

* [Bosch ME7](https://github.com/AndyWhittaker/IDAProBoschMe7x): Siemens Bosch ME7.x Disassembler Helper for IDA Pro

* [CGEN](https://github.com/yifanlu/cgen): CGEN with support for generating IDA Pro IDP modules.

* [Class Informer](http://sourceforge.net/projects/classinformer/): Scans an MSVC 32bit target IDB for vftables with C++ RTTI, and MFC RTCI type data. Places structure defs, names, labels, and comments to make more sense of class vftables ("Virtual Function Table") and make them read easier as an aid to reverse engineering. Creates a list window with found vftables for browsing.

* [codatify](https://github.com/devttys0/ida/tree/master/plugins/codatify):   
    * Defines ASCII strings that IDA's auto analysis missed
    *  Defines functions/code that IDA's auto analysis missed
    *  Converts all undefined bytes in the data segment into DWORDs (thus allowing IDA to resolve function and jump table pointers)

* [c0demap](https://github.com/c0demap/codemap): Codemap is a binary analysis tool for "run-trace visualization" provided as IDA plugin.

* [collabREate](http://www.idabook.com/collabreate/): collabREate is a plugin for IDA Pro that is designed to provide a collaborative reverse engineering capability for multiple IDA users working on the same binary file.

* [Cortex M Firmware](https://github.com/duo-labs/idapython): The Cortex M Firmware module grooms an IDA Pro database containing firmware from an ARM Cortex M microcontroller. This module will annotate the firmware vector table, which contains a number of function pointers. This vector table annotation will cause IDA Pro to perform auto analysis against the functions these pointers point to. 

* [Crowd Detox](https://github.com/CrowdStrike/CrowdDetox): The CrowdDetox plugin for Hex-Rays automatically removes junk code and variables from Hex-Rays function decompilations.

* [Dalvik Header](https://github.com/strazzere/dalvik-header-plugin): This is a simple Dalvik header plugin for IDA Pro

* [Data Xref Counter](https://github.com/onethawt/idapyscripts): Enumerates all of the the x-references in a specific segment and counts the frequency of usage. The plugin displays the data in QtTableWidget and lets the user filter and sort the references. You can also export the data to a CSV file.

* [Debugger](https://github.com/cseagle/sk3wldbg): Debugger plugin for IDA Pro backed by the Unicorn Engine

* [deREferencing](https://github.com/danigargu/deREferencing): IDA Pro plugin that implements more user-friendly register and stack views.

* [Diaphora](https://github.com/joxeankoret/diaphora): Diaphora (διαφορά, Greek for 'difference') is a program diffing plugin for IDA Pro, similar to Zynamics Bindiff or the FOSS counterparts DarunGrim, TurboDiff, etc... It was released during SyScan 2015.

* [Docker IDA](http://blog.intezer.com/docker-ida/): Run IDA Pro disassembler in Docker containers for automating, scaling and distributing the use of IDAPython scripts.

* [DOXBox Debugger](https://github.com/wjp/idados): Eric Fry's IDA/DOSBox debugger plugin

* [DrGadget](https://github.com/patois/DrGadget): This is an IDAPython plugin for the Interactive Disassembler for all your ROP experimentation needs.

* [DriverBuddy](https://github.com/nccgroup/DriverBuddy): DriverBuddy is an IDA Python script to assist with the reverse engineering of Windows kernel drivers.

* [Drop](https://github.com/Riscure/DROP-IDA-plugin): An experimental IDA Pro plugin capable of detecting several types of opaque predicates in obfuscated binaries. It leverages the power of the symbolic execution engine angr and its components to reason about the opaqueness of predicates based on their symbolic context.

* [dsync](https://github.com/patois/dsync): IDAPython plugin that synchronizes decompiled and disassembled code views.

* [dwarfexport](https://github.com/ALSchwalm/dwarfexport): dwarfexport is an IDA Pro plugin that allows the user to export dwarf debug information. This can then be imported in to gdb and other tools, allowing you to debug using info you have recovered in IDA even when you cannot connect the IDA debugger.

* [DWARF Plugin](https://hex-rays.com/contests/2009/IDADwarf-0.2/README): IDADWARF is an IDA plugin that imports DWARF debugging symbols into an IDA database. [Download](https://hex-rays.com/contests/2009/IDADwarf-0.2/idadwarf-0.2.zip)

* [Dynamic Data Resolver](https://github.com/Cisco-Talos/DynDataResolver):  A plugin for IDA that aims to make the reverse-engineering of malware easier. Features: Code Flow Trace, Searchable API call logging, Searchable string logging, Resolving dynamic values and auto-commenting.

* [Dynamic IDA Enrichment](https://github.com/ynvb/DIE): DIE is an IDA python plugin designed to enrich IDA`s static analysis with dynamic data. This is done using the IDA Debugger API, by placing breakpoints in key locations and saving the current system context once those breakpoints are hit.

* [EFI Scripts](https://github.com/danse-macabre/ida-efitools): Some IDA scripts and tools to assist with reverse engineering EFI executables.

* [EtherAnnotate](https://github.com/inositle/etherannotate_ida): Parses the specialized instruction trace files that are generated using the EtherAnnotate Xen modification (http://github.com/inositle/etherannotate_xen).  From the instruction trace, register values and code coverage of the run-time information are visualized in IDA Pro through instruction comments and line colorations.

* [Extract Macho-O](https://github.com/gdbinit/ExtractMachO): This is a very simple IDA plugin to extract all Mach-O binaries contained anywhere in the disassembly.

* [FCatalog](http://www.xorpd.net/pages/fcatalog.html): FCatalog (The functions catalog) is a mechanism for finding similarities between different binary blobs in an efficient manner. It is mostly useful for identifying a new binary blob is somewhat similar to a binary blob that have been encountered before. The client side of FCatalog is an IDA plugin that allows a group of reverse engineers to manage a pool of reversed functions. Whenever a new binary function is encountered, FCatalog can compare it to all the known and previously reversed binary functions.

* [Findcrypt](https://github.com/polymorf/findcrypt-yara): IDA pro plugin to find crypto constants (and more)

* [Flare Plugins](https://github.com/fireeye/flare-ida): Shellcode Hashes, Struct Typer, StackStrings, MSDN Annotations, ApplyCalleType

* [FLS Loader](https://github.com/rpw/flsloader): IDA Pro loader module for IFX iPhone baseband firmwares. Based on a universal scatter loader script by roxfan.

* [Fluorescence](https://github.com/devttys0/ida/tree/master/plugins/fluorescence): Un/highlights function call instructions

* [Free the debuggers](https://github.com/techbliss/Free_the_Debuggers): Free the ida pro debuggers for all files.

* [Frida](https://github.com/techbliss/Frida_For_Ida_Pro): This is plugin for ida pro thar uses the Frida api. Mainly trace functions.

* [FRAPL](https://github.com/FriedAppleTeam/FRAPL): FRAPL is a reverse engineering framework created to simplify dynamic instrumentation with Frida.

* [FRIEND](https://github.com/alexhude/FRIEND): Flexible Register/Instruction Extender aNd Documentation. FRIEND is an IDA plugin created to improve disassembly and bring register/instruction documentation right into IDA View.

* [Funcap](https://github.com/deresz/funcap): This script records function calls (and returns) across an executable using IDA debugger API, along with all the arguments passed. It dumps the info to a text file, and also inserts it into IDA's inline comments. This way, static analysis that usually follows the behavioral runtime analysis when analyzing malware, can be directly fed with runtime info such as decrypted strings returned in function's arguments.

* [Functions+](https://github.com/nihilus/functions-plus): IDA Pro plugin to make functions tree view. Plugin parses function names and groups them by namespaces.

* [Function Tagger](https://github.com/alessandrogario/IDA-Function-Tagger): This IDAPython script tags subroutines according to their use of imported functions

* [Gamecube Extension](https://github.com/hyperiris/gekkoPS): This is a Gekko CPU Paired Single extension instructions plug-in for IDA Pro 5.2

* [Gamecube DSP](https://github.com/dolphin-emu/gcdsp-ida): This project adds support for the DSP present in the Gamecube and the Wii to IDA, the Interactive Disassembler [1]. This allows easy analyze of a DSP ucode, handling cross-references, control flow, and so on.

* [genmc](https://github.com/patois/genmc): Genmc is an IDAPython script/plugin hybrid that displays Hexrays decompiler microcode, which can help in developing microcode plugins.

* [Gensida](https://github.com/lab313ru/Gensida): IDA debugger plugin for Sega Genesis / Megadrive ROMs based on Gens ReRecordings emulator modifications.

* [Geolocator](https://github.com/techbliss/ida_pro_http_ip_geolocator): Lookup IP's and http/https adresses, using google maps, and MaxMind databases.

* [gdbida](https://github.com/comsecuris/gdbida): A visual bridge between a GDB session and IDA Pro's disassembler

* [golang_loader_assist](https://github.com/strazzere/golang_loader_assist): Making GO reversing easier in IDA Pro

* [Graph Slick](https://github.com/lallousx86/GraphSlick): Automated detection of inlined functions. It highlights similar groups of nodes and allows you to group them, simplifying complex functions. The authors provide an accompanying presentation which explains the algorithms behind the plugin and shows sample use cases.

* [HeapViewer](https://github.com/danigargu/heap-viewer): An IDA Pro plugin to examine the heap, focused on exploit development.

* [HexRays CodeXplorer](https://github.com/REhints/HexRaysCodeXplorer): The Hex-Rays Decompiler plugin for better code navigation in RE process. CodeXplorer automates code REconstruction of C++ applications or modern malware like Stuxnet, Flame, Equation, Animal Farm ...

* [HexRaysDeob](https://www.hex-rays.com/contests/2018/index.shtml): A Hex-Rays microcode API plugin breaking an obfuscating compiler used to create an in-the-wild malware family. The plugin is fully automatic and requires no user intervention; upon installation, the decompilation listings presented to the user will be free of obfuscation.

* [HexRays Tools](https://github.com/nihilus/hexrays_tools): 
  * Assist in creation of new structure definitions / virtual calls detection
  * Jump directly to virtual function or structure member definition
  * Gives list of structures with given size, with given offset
  * Finds structures with same "shape" as is used.
  * convert function to __usercall or __userpurge
  * and more....
  
* [HexRaysPyTools](https://github.com/igogo-x86/HexRaysPyTools): Plugin assists in creation classes/structures and detection virtual tables. Best to use with Class Informer plugin, because it helps to automatically get original classes names.

* [HRDEV](https://github.com/ax330d/hrdev): This is an IDA Pro Python plugin to make Hex-Rays Decompiler output bit more attractive. HRDEV plugin retrieves standard decompiler output, parses it with Python Clang bindings, does some magic, and puts back.

* [HrDevHelper](https://github.com/patois/HRDevHelper): HexRays decompiler plugin that visualizes the ctree of decompiled functions using IDA's graph engine.

* [Hyara](https://www.hex-rays.com/contests/2018/index.shtml): A plugin to create pattern-matching rules. It helps creating rules for the YARA pattern-matching tool direcly in IDA. It includes a simple detection of relocatable bytes in x86 opcodes for improved matching. It also provides a checker feature for testing the rules on the loaded binary.

* [IDA2SQL](https://github.com/zynamics/ida2sql-plugin-ida): As the name implies this plugin can be used to export information from IDA databases to SQL databases. This allows for further analysis of the collected data: statstical analysis, building graphs, finding similarities between programs, etc.

* [IDA ARM](https://github.com/gdelugre/ida-arm-system-highlight): This script will give you the list of ARM system instructions used in your IDA database. This is useful for locating specific low-level pieces of code (setting up the MMU, caches, fault handlers, etc.).

* [idawasm](https://github.com/fireeye/idawasm): These IDA Pro plugins add support for loading and disassembling WebAssembly modules.
  * control flow reconstruction and graph mode
  * code and data cross references
  * globals, function parameters, local variables, etc. can be renamed
  * auto-comment hint suport

* [IDA Batch Decompile](https://github.com/tintinweb/ida-batch_decompile): IDA Batch Decompile is a plugin for Hex-Ray's IDA Pro that adds the ability to batch decompile multiple files and their imports with additional annotations (xref, stack var size) to the pseudocode .c file

* [IDABuddy](https://github.com/tmr232/IDABuddy): IDABuddy is a reverse-engineer's best friend. Designed to be everything Clippy the Office Assistant was, and more!

* [IDA C#](https://github.com/Fabi/IDACSharp): Scripting IDA with C#

* [IDA Compare](https://github.com/dzzie/IDACompare): IDA disassembly level diffing tool, find patches and modifications between malware variants. See mydoom A/B sample database and video trainer for usage.

* [IDACyber](https://github.com/patois/IDACyber): IDACyber is a plugin for the Interactive Disassembler that visualizes an IDA database's content.

* [IDA EA](https://github.com/1111joe1111/ida_ea): Provides a context viewer,  instruction emulator, heap explorer, trace dumper, GDB integration, Styling

* [IDA Emu](https://github.com/36hours/idaemu): idaemu is an IDA Pro Plugin - use for emulating code in IDA Pro. it is base on unicorn-engine.

* [IDA Eye](http://www.mfmokbel.com/Down/RCE/Documentation.html): Plugin that enables you to perform different operations at the mnemonic level, independent of any particular processor type. These operations are facilitated through a parameterized template, which include the capabilities to de/highlight instructions, gather statistical information about the frequency of each instruction, and search for sequences of mnemonics, among other features.

* [IDA Extrapass](http://sourceforge.net/projects/idaextrapassplugin/): An IDA Pro Win32 target clean up plug-in by Sirmabus. It does essentially four cleaning/fixing steps: Convert stray code section values to "unknown", fix missing "align" blocks, fix missing code bytes, and locate and fix missing/undefined functions.

* [IDAFuzzy](https://github.com/Ga-ryo/IDAFuzzy): IDAFuzzy is fuzzy searching tool for IDA Pro. This tool helps you to find command/function/struct and so on.

* [idaidle](https://github.com/google/idaidle): idaidle is a plugin for the commercial IDA Pro disassembler that warns users if they leave their instance idling for too long. After a predetermined amount of idle time, the plugin first warns and later then saves the current disassemlby database and closes IDA.

* [IDA Images](https://github.com/rr-/ida-images): Image preview plugin for IDA disassembler.

* [IDA IPython](https://github.com/james91b/ida_ipython): This is a plugin to embed an IPython kernel in IDA Pro. The Python ecosystem has amazing libraries (and communities) for scientific computing. IPython itself is great for exploratory data analysis. Using tools such as the IPython notebook make it easy to share code and explanations with rich media. IPython makes using IDAPython and interacting with IDA programmatically really fun and easy.

* [IDAngr](https://github.com/andreafioraldi/IDAngr): Use angr in the ida debugger generating a state from the current debug session 

* [IDA BPF Processor](https://github.com/bnbdr/ida-bpf-processor): BPF Bytecode Processor for IDA (python). Supports the old BPF bytecode only (no eBPF).

* [IDAMagicStrings](https://github.com/joxeankoret/idamagicstrings): An IDA Python plugin to extract information from string constants. The current version of the plugin is able to:
  * Display functions to source files relationships (in a tree and in a plain list, a chooser in IDA language).
  * Display guessed function names for functions.
  * Rename functions according to the source code file their belong + address (for example, memory_mgmt_0x401050).
  * Rename functions according to the guessed function name.

* [idamagnum](https://github.com/lucasg/idamagnum): A plugin for integrating MagnumDB requests within IDA. MagNumDB is a database that contains about 380,000 items. These items are constants, names, values all extracted from more than 6,000 header files (.h, .hxx, .hpp, .idl, etc.) provided by standard Windows and Visual Studio SDKs and WDKs. 

* [IDA-minsc](https://github.com/arizvisa/ida-minsc): A plugin that assists a user with scripting the IDAPython plugin that is bundled with the disassembler. This plugin groups the different aspects of the IDAPython API into a simpler format which allows a reverse engineer to script different aspects of their work with very little investment.

* [IDA Patchwork](https://bitbucket.org/daniel_plohmann/idapatchwork): Stitching against malware families with IDA Pro (tool for the talk at Spring9, https://spring2014.gdata.de/spring2014/programm.html). In essence, I use a somewhat fixed / refurbished version of PyEmu along IDA to demonstrate deobfuscation of the different patterns found in the malware family Nymaim.

* [IDA Python Embedded Toolkit](https://github.com/maddiestone/IDAPythonEmbeddedToolkit): IDAPython scripts for automating analysis of firmware of embedded devices.

* [IDARay](https://github.com/SouhailHammou/IDARay-Plugin): IDARay is an IDA Pro plugin that matches the database against multiple YARA files. Maybe your rules are scattered over multiple YARA files or you simply want to match against as much rules as possible, IDARay is here to help.

* [IDA Ref](https://github.com/nologic/idaref): IDA Pro Full Instruction Reference Plugin - It's like auto-comments but useful.

* [IDA Rest](https://github.com/dshikashio/idarest): A simple REST-like API for basic interoperability with IDA Pro.

* [IDArling](https://github.com/IDArlingTeam/IDArling/): IDArling is a collaborative reverse engineering plugin for IDA Pro and Hex-Rays. It allows to synchronize in real-time the changes made to a database by multiple users, by connecting together different instances of IDA Pro.

* [IDA Scope](https://bitbucket.org/daniel_plohmann/simplifire.idascope): IDAscope is an IDA Pro extension with the goal to ease the task of (malware) reverse engineering with a current focus on x86 Windows. It consists of multiple tabs, containing functionality to achieve different goals such as fast identification of semantically interesting locations in the analysis target, seamless access to MSDN documentation of Windows API, and finding of potential crypto/compression algorithms.

* [IDA Signature Matching Tool](http://sourceforge.net/projects/idasignsrch/): Tool for searching signatures inside files, extremely useful as help in reversing jobs like figuring or having an initial idea of what encryption/compression algorithm is used for a proprietary protocol or file. It can recognize tons of compression, multimedia and encryption algorithms and
many other things like known strings and anti-debugging code which can be also manually added since it's all based on a text signature file read at run-time and easy to modify.

* [IDA Skins](https://github.com/zyantific/IDASkins): Plugin providing advanced skinning support for the Qt version of IDA Pro utilizing Qt stylesheets, similar to CSS.

* [IDA Sploiter](http://thesprawl.org/projects/ida-sploiter/): IDA Sploiter is a plugin for Hex-Ray's IDA Pro disassembler designed to enhance IDA's capabilities as an exploit development and vulnerability research tool. Some of the plugin's features include a powerful ROP gadgets search engine, semantic gadget analysis and filtering, interactive ROP chain builder, stack pivot analysis, writable function pointer search, cyclic memory pattern generation and offset analysis, detection of bad characters and memory holes, and many others.

* [IDA Stealth](http://newgre.net/idastealth): IDAStealth is a plugin which aims to hide the IDA debugger from most common anti-debugging techniques. The plugin is composed of two files, the plugin itself and a dll which is injected into the debuggee as soon as the debugger attaches to the process. The injected dll actually implements most of the stealth techniques either by hooking system calls or by patching some flags in the remote process.

* [IDA StringCluster](https://github.com/Comsecuris/ida_strcluster): This plugin extends IDA Pro's capabilities to display strings within the binary by clustering found strings on a per-function basis.

* [IDA Toolbag](https://github.com/aaronportnoy/toolbag): The IDA Toolbag plugin provides many handy features, such as:
  * A 'History' view, that displays functions in the disassembly that you have decided are important, and the relationships between them.
  * A code path-searching tool, that lets you find what functions (or blocks) are forming a path between two locations.
  * Manage and run your IDC/Python scripts
  * Something that's also of considerable importance is that the IDA Toolbag lets you collaborate with other IDA users: one can publish his 'History', or import another user's history & even merge them!
  * See the official documentation for an extensive feature list.

* [IdaVSHelp](https://github.com/andreafioraldi/IdaVSHelp): IDAPython plugin to integrate Visual Studio Help Viewer in IDA Pro >= 6.8

* [IDAtropy](https://github.com/danigargu/IDAtropy): IDAtropy is a plugin for Hex-Ray's IDA Pro designed to generate charts of entropy and histograms using the power of idapython and matplotlib.

* [IDA Xtensa](https://github.com/themadinventor/ida-xtensa): This is a processor plugin for IDA, to support the Xtensa core found in Espressif ESP8266. It does not support other configurations of the Xtensa architecture, but that is probably (hopefully) easy to implement.

* [idb2pat](https://github.com/alexander-pick/idb2pat): IDB to Pat.

* [IFL](https://github.com/hasherezade/ida_ifl): Interactive Functions List is an user-friendly way to navigate between functions and their references.

* [ifred](https://github.com/Jinmo/ifred): IDA command palette & further

* [ioctl_plugin](https://github.com/sam-b/ioctl_plugin): A tool to help when dealing with IOCTL codes and Windows driver IOCTL dispatch functions.

* [IPyIDA](https://github.com/eset/ipyida): PyIDA is a python-only solution to use a IPython console in the context of IDA Pro. It spawns an IPython kernel that you can connect to with `ipython console --existing` in your shell or by opening a *QT Console* window in IDA Pro with `<Shift-.>`

* [Kam1n0](https://github.com/McGill-DMaS/Kam1n0-Plugin-IDA-Pro): Kam1n0 is a scalable system that supports assembly code clone search. It allows a user to first index a (large) collection of binaries, and then search for the code clones of a given target function or binary file. Kam1n0 tries to solve the efficient subgraph search problem (i.e. graph isomorphism problem) for assembly functions.

* [Karta](https://github.com/CheckPointSW/Karta): "Karta" (Russian for "Map") is a source code assisted fast binary matching plugin for IDA. Karta identifies and matches open-sourced libraries in a given binary using a unique technique that enables it to support huge binaries (> 200,000 functions) with almost no impact on the overall performance.

* [Keypatch](http://keystone-engine.org/keypatch): A multi-architeture assembler for IDA. Keypatch allows you enter assembly instructions to directly patch the binary under analysis. Powered by [Keystone engine](http://keystone-engine.org).

* [Labeless](https://github.com/a1ext/labeless): Labeless is a plugin system for dynamic, seamless and realtime synchronization between IDA Database and Olly. Labels, function names and global variables synchronization is supported. 
Labeless provides easy to use dynamic dumping tool, which supports automatic on-the-fly imports fixing as well as convenient tool for IDA-Olly Python scripting synergy.

* [LazyIDA](https://github.com/L4ys/LazyIDA): LazyIDA lets you perform many tasks simply and quickly (e.g., remove function return type in Hex-Rays, convert data into different formats, scan for format string vulnerabilities and a variety of shortcuts)

* [Lighthouse](https://github.com/gaasedelen/lighthouse): Lighthouse is a Code Coverage Plugin for IDA Pro. The plugin leverages IDA as a platform to map, explore, and visualize externally collected code coverage data when symbols or source may not be available for a given binary.

* [LoadProcConfig](https://github.com/alexhude/LoadProcConfig): LoadProcConfig is an IDA plugin to load processor configuration files.

* [Localxrefs](https://github.com/devttys0/ida/tree/master/plugins/localxrefs): Finds references to any selected text from within the current function.

* [MadNES](https://github.com/patois/MadNES): This plugin exports IDA names to FCEUXD SP symbols.

* [MazeWalker](https://github.com/0xPhoeniX/MazeWalker): Toolkit for enriching and speeding up static malware analysis. MazeWalker’s goal is to reduce malware analysis time by automating runtime data collection and better visualization eventually helping a researcher to concentrate on static analysis and less on its dynamic part.

* [MC68K Processor Model Extension](https://github.com/LucienMP/idapro_m68k): This is a sample plugin for extending gdb support for step-over for the M68K, and to enable type information support so you can press "y" on functions and have the parameters propagate inside and back out of the function.

* [mipslocalvars](https://github.com/devttys0/ida/tree/master/plugins/mipslocalvars): Names stack variables used by the compiler for storing registers on the stack, simplifying stack data analysis (MIPS only)

* [mipsrop](https://github.com/devttys0/ida/tree/master/plugins/mipsrop):
    * Allows you to search for suitable ROP gadgets in MIPS executable code
    * Built-in methods to search for common ROP gadgets

* [MrsPicky](https://github.com/patois/mrspicky): An IDAPython decompiler script that helps auditing calls to the memcpy() and memmove() functions.

* [MSDN Helper](https://github.com/Z-Rantom/IMH): This tool will help you to get to Offline MSDN help while using IDA Pro.

* [MyNav](https://code.google.com/p/mynav/): MyNav is a plugin for IDA Pro to help reverse engineers in the most typical task like discovering what functions are responsible of some specifical tasks, finding paths between "interesting" functions and data entry points.

* [nao](https://github.com/tkmru/nao): nao(no-meaning assembly omiter) is dead code eliminator plugin for IDA pro

* [NDSLdr](https://github.com/patois/NDSLdr): Nintendo DS ROM loader module for IDA Pro.

* [NECromancer](https://github.com/patois/NECromancer): IDA Pro V850 Processor Module Extension.

* [NES Loader](https://github.com/patois/nesldr): Nintendo Entertainment System (NES) ROM loader module for IDA Pro.

* [NIOS2](https://www.hex-rays.com/contests/2018/index.shtml): An IDA Pro processor module for Altera Nios II Classic/Gen2 microprocessor architecture.

* [NSIS Reversing Suite](https://github.com/isra17/nrs/): NRS is a set of Python librairies used to unpack and analysis NSIS installer's data. It also feature an IDA plugin used to disassembly the NSIS Script of an installer.

* [Optimice](https://code.google.com/p/optimice/): This plugin enables you to remove some common obfuscations and rewrite code to a new segment. Currently supported optimizations are: Dead code removal, JMP merging, JCC opaque predicate removal, Pattern based deobfuscations

* [Oregami](https://www.hex-rays.com/contests/2018/index.shtml): A plugin analyzing the current function to find the usage frame of registers. Oregami eases the work when tracking the use of a register within a function, by limiting the search to occurrences related to the one currently highlighted instead of the whole function.

* [Patcher](https://github.com/iphelix/ida-patcher): IDA Patcher is a plugin for Hex-Ray's IDA Pro disassembler designed to enhance IDA's ability to patch binary files and memory.

* [Plus22](https://github.com/v0s/plus22): Plus22 transforms x86_64 executables to be processed with 32-bit version of Hex-Rays Decompiler.

* [Plympton](https://github.com/rogwfu/plympton): A gem to read program disassembly from a YAML dump. The YAML dump is generated from an IDA Pro python script. This script is included along with this Gem (func.py)

* [Pomidor](https://github.com/iphelix/ida-pomidor): IDA Pomidor is a plugin for Hex-Ray's IDA Pro disassembler that will help you retain concentration and productivity during long reversing sessions.

* [Ponce](https://github.com/illera88/Ponce): Taint analysis and symbolic execution over binaries in an easy and intuitive fashion.

* [Prefix](https://github.com/gaasedelen/prefix): Prefix is a small function prefixing plugin for IDA Pro. The plugin augments IDA's function renaming capabilities by adding a handful of convenient prefixing actions to relevant right click menus.

* [Processor changer](https://github.com/techbliss/Processor-Changer): Change processor without restarting IDA.

* [Python Editor](https://github.com/techbliss/Python_editor): Python editor based IDA Pro. The plugin helps python devs with scripting and running python scripts, and creating them. IT have many functions, code recognition and more.

* [qb-sync](https://github.com/quarkslab/qb-sync): qb-sync is an open source tool to add some helpful glue between IDA Pro and Windbg. Its core feature is to dynamically synchronize IDA's graph windows with Windbg's position.

* [Qualcomm Loader](https://github.com/daxgr/qcom-mbn-ida-loader): IDA loader plugin for Qualcomm Bootloader Stages

* [Recompiler](https://github.com/bastkerg/Recomp): IDA recompiler

* [Reef](https://github.com/darx0r/Reef): IDAPython plugin for finding Xrefs from a function.

* [REobjc](https://github.com/duo-labs/idapython): REobjc is an IDAPython module designed to make proper cross references between calling functions and called functions in Objective-C methods. The current form of the module supports X64, and will be updated to also support ARM in the future.

* [REProgram](https://github.com/jkoppel/REProgram): A way of making almost-arbitrary changes to an executable when run under a debugger -- even changes that don't fit.

* [retdec](https://retdec.com/idaplugin/): IDA plugin for retdec - a retargetable machine-code decompiler based on LLVM.

* [ret-sync](https://github.com/bootleg/ret-sync): ret-sync stands for Reverse-Engineering Tools synchronization. It's a set of plugins that help to synchronize a debugging session (WinDbg/GDB/LLDB/OllyDbg2/x64dbg) with IDA disassembler. The underlying idea is simple: take the best from both worlds (static and dynamic analysis).

* [REtypedef](https://github.com/zyantific/REtypedef): REtypedef is an IDA PRO plugin that allows defining custom substitutions for function names. It comes with a default ruleset providing substitutions for many common STL types.

* [rizzo](https://github.com/devttys0/ida/tree/master/plugins/rizzo): Identifies and re-names functions between two or more IDBs based on:
    * Formal signatures (i.e., exact function signatures)
    * References to unique string
    * References to unique constants
    * Fuzzy signatures (i.e., similar function signatures)
    * Call graphs (e.g., identification by association)

* [Samsung S4 Rom Loader](https://github.com/cycad/mbn_loader): IDA Pro Loader Plugin for Samsung Galaxy S4 ROMs

* [Sark](https://github.com/tmr232/Sark/): Sark, (named after the notorious Tron villain,) is an object-oriented scripting layer written on top of IDAPython. Sark is easy to use and provides tools for writing advanced scripts and plugins.

* [ScratchABit](https://github.com/pfalcon/ScratchABit): ScratchABit is an interactive incremental disassembler with data/control flow analysis capabilities. ScratchABit is dedicated to the efforts of the OpenSource reverse engineering community (reverse engineering to produce OpenSource drivers/firmware for hardware not properly supported by vendors).

* [Screen recorder](https://github.com/techbliss/Ida_Pro_Screen_Recorder): IDA Pro Qt Plugin for recording reversing sessions.

* [Sega Genesis/Megadrive Tools](https://github.com/DrMefistO/smd_ida_tools): Special IDA Pro tools for the Sega Genesis/Megadrive romhackers. Tested work on v5.2, v6.6. Should work on other versions.

* [Sig Maker](https://tuts4you.com/download.php?view.3263): Can create sigs automatically and has a wide variety of functions (might be unstable on IDA 6.2).

* [SimplifyGraph](https://github.com/fireeye/SimplifyGraph): An IDA Pro plugin to assist with complex graphs.

* [Simulator](https://github.com/nihilus/IDASimulator): IDASimulator is a plugin that extends IDA's conditional breakpoint support, making it easy to augment / replace complex executable code inside a debugged process with Python code.

* [Snippt Detector](https://github.com/zaironne/SnippetDetector): Snippet Detector is an IDA Python scripts project used to detect snippets from 32bit disassembled files. snippet is the word used to identify a generic sequence of instructions (at the moment a snippet is indeed a defined function). The aim of the tool is to collect many disassembled snippets inside a database for the detection process.

* [Snowman Decompiler](http://derevenets.com/): Snowman is a native code to C/C++ decompiler. Standalone and IDA Plugin. [Source Code](https://github.com/yegord/snowman)

* [Splode](https://github.com/zachriggle/ida-splode): Augmenting Static Reverse Engineering with Dynamic Analysis and Instrumentation

* [spu3dbg](https://github.com/revel8n/spu3dbg): Ida Pro debugger module for the anergistic SPU emulator.

* [Stingray](https://github.com/darx0r/Stingray): Stingray is an IDAPython plugin for finding function strings. The search is from the current position onwards in the current function. It can do it recursively also with configurable search depth. The results order is the natural order of strings in the BFS search graph.

* [Structure Dump](http://www.openrce.org/downloads/details/227/Structure_Dump): StructDump is an IDA plugin, allowing you to export IDA types into high-level language definitions. Currently, C++ is supported.

* [Styler](https://github.com/techbliss/IDA-Styler): Small Plugin to change the style off Ida Pro

* [Synergy](https://github.com/CubicaLabs/IDASynergy): A combination of an IDAPython Plugin and a control version system that result in a new reverse engineering collaborative addon for IDA Pro. By http://cubicalabs.com/

* [sysm2elf](https://github.com/danigargu/syms2elf): A plugin for IDA Pro and radare2 to export the symbols recognized to the ELF symbol table.

* [Tarkus](https://github.com/tmr232/Tarkus): Tarkus is a plugin manager for IDA Pro, modelled after Python's pip.

* [TurboDiff](http://www.coresecurity.com/corelabs-research/open-source-tools/turbodiff): Turbodiff is a binary diffing tool developed as an IDA plugin. It discovers and analyzes differences between the functions of two binaries.

* [uEmu](https://github.com/alexhude/uEmu): uEmu is a tiny cute emulator plugin for IDA based on unicorn engine. Supports following architectures out of the box: x86, x64, ARM, ARM64, MIPS, MIPS64

* [UEFI_RETool](https://github.com/yeggor/UEFI_RETool/tree/master/ida_plugin): IDA Plugin for UEFI firmware executable images analysing

* [Virtuailor](https://github.com/0xgalz/Virtuailor): Virtuailor is an IDAPython tool that reconstructs vtables for C++ code written for intel architechture and both 32bit and 64bit code.

* [VirusBattle](https://github.com/axmat/virusbattle-ida-plugin): The plugin is an integration of Virus Battle API to the well known IDA Disassembler. Virusbattle is a web service that analyses malware and other binaries with a variety of advanced static and dynamic analyses.

* [VMAttack](https://github.com/anatolikalysch/VMAttack): Static and dynamic virtualization-based packed analysis and deobfuscation.

* [Win32 LST to Inline Assembly](https://github.com/binrapt/ida): Python script which extracts procedures from IDA Win32 LST files and converts them to correctly dynamically linked compilable Visual C++ inline assembly.

* [WinIOCtlDecoder](https://github.com/tandasat/WinIoCtlDecoder): An IDA Pro plugin which decodes a Windows Device I/O control code into DeviceType, FunctionCode, AccessType and MethodType.

* [Xex Loader for IDA 6.6](http://xorloser.com/blog/?p=395): This adds the ability to load xex files into IDA directly without having to first process them in any way. It processes the xex file as much as possible while loading to minimise the work required by the user to get it to a state fit for reversing.

* [X86Emu](http://www.idabook.com/ida-x86emu/):  Its purpose is to allow a reverse engineer the chance to step through x86 code while reverse engineering a binary.  The plugin can help you step through any x86 binary from any platform. For Windows binaries, many common library calls are trapped and emulated by the emulator, allowing for a higher fidelity emulation. I find it particularly useful for stepping through obfuscated code as it automatically reorganizes an IDA disassembly based on actual code paths.

* [YaCo](https://github.com/DGA-MI-SSI/YaCo) : Collaboration Plugin : when enabled, an unlimited number of users can work simultaneously on the same binary. Any modification done by any user is synchronized through git version control. It has been initially released at [SSTIC 2017](https://www.sstic.org/2017/presentation/YaCo/)

* [Zynamics BinDiff](http://www.zynamics.com/bindiff.html): BinDiff is a comparison tool for binary files, that assists vulnerability researchers and engineers to quickly find differences and similarities in disassembled code.

## Commercial Plugins
