Command exited with code 0.

Command output:
## evidence_id

ev_b2b9ee61127cfe3c458e65fcae77bf012339a279b872b2b6b728aa3d789a0375

## evidence_format

2

## subject.identity

| Key          | Value                                                            |
|--------------|------------------------------------------------------------------|
| kind         | file                                                             |
| sha256       | b7e244748566f66789723d28eaf59fcd4e0c35b466948bb558d26e1037eb2217 |
| selection    | null                                                             |
| format       | pe                                                               |
| architecture | x86_64                                                           |

## subject.name

CapCut.exe

## subject.local_path

C&#58;\\Users\\Usuario\\AppData\\Local\\CapCut\\Apps\\9.8.0.4213\\CapCut.exe

## provider

| Key     | Value                               |
|---------|-------------------------------------|
| id      | rea-workflow                        |
| name    | REA composed investigation workflow |
| version | 1                                   |

## analysis_profile.provider

| Key     | Value                               |
|---------|-------------------------------------|
| id      | rea-workflow                        |
| name    | REA composed investigation workflow |
| version | 1                                   |

## analysis_profile.parameters.upstream_analysis_profile.provider

| Key     | Value  |
|---------|--------|
| id      | ghidra |
| name    | Ghidra |
| version | 12.2   |

## analysis_profile.parameters.upstream_analysis_profile.parameters.target_kind

executable

## analysis_profile.parameters.upstream_analysis_profile.parameters.target_format

pe

## analysis_profile.parameters.upstream_analysis_profile.parameters.executable_role

application

## analysis_profile.parameters.upstream_analysis_profile.parameters.managed

false

## analysis_profile.parameters.upstream_analysis_profile.parameters.native_aot_metadata

| Key                        | Value     |
|----------------------------|-----------|
| source_bytes               | 134217728 |
| base_work_units            | 67108864  |
| work_units_per_source_byte | 8         |
| working_memory_bytes       | 67108864  |
| report_bytes               | 4194304   |

## analysis_profile.parameters.upstream_analysis_profile.parameters.architecture

x86_64

## analysis_profile.parameters.upstream_analysis_profile.parameters.available_architectures

\["x86_64"\]

## analysis_profile.parameters.upstream_analysis_profile.parameters.import_mode

ephemeral-source-immutable

## analysis_profile.parameters.upstream_analysis_profile.parameters.producer

| Key            | Value                                                            |
|----------------|------------------------------------------------------------------|
| rea_version    | 6.10.1                                                           |
| sources_sha256 | 2acc01df6e538ba5171b72dc8d8b1752a57b3dacd670979ea84a07661bd7ef1f |

## analysis_profile.parameters.upstream_analysis_profile.parameters.annotation_policy

atomic-function-entry-metadata

## analysis_profile.parameters.upstream_analysis_profile.parameters.loader_relocation_semantics

read-only-relocation-limitations

## analysis_profile.parameters.upstream_analysis_profile.parameters.no_return_repair

disabled-windows-p0

## analysis_profile.parameters.upstream_analysis_profile.parameters.process_launch

official-headless-script

## analysis_profile.parameters.upstream_analysis_profile.parameters.decompiler_jump_loads

true

## analysis_profile.parameters.upstream_analysis_profile.parameters.loader

auto-from-header

## analysis_profile.parameters.upstream_analysis_profile.parameters.language_id

auto-from-header

## analysis_profile.parameters.upstream_analysis_profile.parameters.compiler_spec_id

auto-default

## analysis_profile.parameters.upstream_analysis_profile.parameters.analyzer_preset

ghidra-default

## analysis_profile.parameters.upstream_analysis_profile.parameters.function_coordinate_context

| Key            | Value                                                            |
|----------------|------------------------------------------------------------------|
| kind           | native-function-coordinate-context-v1                            |
| selected_image | null                                                             |
| mapping_sha256 | 55a7964dc0bcdf067484a281c658e6ca8457a49405e0ea9dbd080366ee4c3198 |

## analysis_profile.parameters.upstream_analysis_profile.digest

1e8cc6f9f7acf6ac27583d94db4a5097fdc9714d605d1a89af9f24e8e922725c

## analysis_profile.parameters.source_limitations

provider-operation-caveats-v1

## analysis_profile.parameters.workflow_revision

5

## analysis_profile.digest

e047456df582317185801afb60a31ada4e0dcad41c376793cecf45814e948738

## predicate_type

rea.analysis

## operation

binary_overview

## parameters

| Key | Value |
|-----|-------|

## raw_result

null

## normalized_result.document

target-b7e244748566.exe

## normalized_result.image_base

0x140000000

## normalized_result.segments

| name    | start        | end          | length | image_base  | address_space |
|---------|--------------|--------------|--------|-------------|---------------|
| Headers | 0x140000000  | 0x140000400  | 1024   | 0x140000000 | ram           |
| .text   | 0x140001000  | 0x140007000  | 24576  | 0x140000000 | ram           |
| .rdata  | 0x140007000  | 0x14000c000  | 20480  | 0x140000000 | ram           |
| .data   | 0x14000c000  | 0x14000d000  | 4096   | 0x140000000 | ram           |
| .pdata  | 0x14000d000  | 0x14000e000  | 4096   | 0x140000000 | ram           |
| .rsrc   | 0x14000e000  | 0x140017000  | 36864  | 0x140000000 | ram           |
| .reloc  | 0x140017000  | 0x140018000  | 4096   | 0x140000000 | ram           |
| tdb     | 0xff00000000 | 0xff00001850 | 6224   | 0x140000000 | ram           |

## normalized_result.segment_count

8

## normalized_result.procedure_count

323

## normalized_result.string_count

226

## normalized_result.inventory_coverage

| Key                | Value              |
|--------------------|--------------------|
| scope              | provider_inventory |
| discovery_coverage | unknown            |

## confidence

derived

## authority

shipped-artifact

## environment

null

## limitations

\["Derived by an REA composed workflow.","Ghidra (ghidra 12.2) read_binary_inventory_summary&#58; Cancelling an active Ghidra request terminates its ephemeral database and discards session annotations. The selected target remains open; the next provider query imports the original artifact again.","Ghidra (ghidra 12.2) read_binary_inventory_summary&#58; Counts use the complete defined-string inventory and the same local/external function inventory as list_strings and list_procedures. They do not establish discovery of undefined strings or unidentified functions.","Ghidra (ghidra 12.2) read_binary_inventory_summary&#58; Default-space addresses use lowercase 0x-prefixed hexadecimal; other address spaces use &lt;percent-encoded-space&gt;&#58;0x&lt;hex&gt;.","Ghidra (ghidra 12.2) read_binary_inventory_summary&#58; Ghidra Program checkpoint mode is disabled&#58; closing discards metadata edits; original executable bytes are unchanged. For stock ELF/PE/Mach-O on Linux/macOS, set REA_GHIDRA_CHECKPOINT_DIR to a private absolute directory before starting REA (restart MCP after changing its startup environment).","Ghidra (ghidra 12.2) read_binary_inventory_summary&#58; Known provider defect ghidra-10154 (jump-table-unrecovered-function-truncated)&#58; Ghidra 12.2 leaves an aarch64 switch unrecovered when it is a byte-offset bounded by and-0xff. The function body stops at the indirect branch. Upstream issue https&#58;//github.com/NationalSecurityAgency/ghidra/issues/10154 is open and names a Swift -O swift-enum switch; it has no fix commit and no milestone. REA reproduced the unrecovered jump table on the exact 12.2 build with an AArch64 ELF object of that instruction shape. A compare-bounded byte table still recovers. This record stays on every admitted build until a release is known to clear it.","Ghidra (ghidra 12.2) read_binary_inventory_summary&#58; Known provider defect ghidra-9996 (jump-table-flow-references-omitted)&#58; Ghidra 12.2 can omit jump-table flow references and emit incorrect decompiler output for clang -O0 x86-64 switches whose case labels start above zero. Upstream issue https&#58;//github.com/NationalSecurityAgency/ghidra/issues/9996 is closed by c93917a622211349998f641de54cfdbe0e0e5bee, milestone 12.2.1, which is not yet released. This limitation is recorded for parsed 12.2 releases whose patch is below 12.2.1, including a zero patch and a suffix, and clears on 12.2.1. REA's verified switch lane compiles with -O2 and does not cover this shape.","Ghidra (ghidra 12.2) read_binary_inventory_summary&#58; Memory-block end addresses are exclusive; segment lengths use those observed address coordinates.","Ghidra (ghidra 12.2) read_binary_inventory_summary&#58; Only Ghidra-defined string Data is observed; packed or undefined string bytes may be absent. Completeness applies to that inventory, and an empty search does not establish that text is absent from the artifact. If an address is known, use read_bytes and xrefs to inspect bytes and references.","Ghidra (ghidra 12.2) read_binary_inventory_summary&#58; The Ghidra Program references PDB CapCut.pdb (GUID 8bba7091-afe8-486c-af8c-2f54b31fba63, age (hex) 1, signature unknown, version RSDS); Ghidra reports load state unknown. Original names and types may be missing; an empty name search does not prove a procedure is absent. Use list_procedures and address-based analysis to inspect recovered functions. REA does not admit a caller-selected PDB companion.","Ghidra (ghidra 12.2) read_binary_inventory_summary&#58; The Windows bridge uses authenticated IPv4 loopback because Node path-based IPC does not expose Java AF_UNIX sockets; the endpoint file contains no bearer token.","Ghidra (ghidra 12.2) read_binary_inventory_summary&#58; The session serves operations only after Ghidra reports default auto-analysis complete; incomplete analysis does not expose partial results.","Ghidra (ghidra 12.2) read_binary_inventory_summary&#58; Windows Ghidra P0 accepts native x86, x86-64, ARMNT (Thumb-2) and ARM64 PE applications and DLLs, DOS MZ images, and explicitly selected raw 6502 images; managed, hostile, sensitive, and mutable-path targets are unsupported.","Ghidra (ghidra 12.2) read_binary_inventory_summary&#58; Windows sessions require the matching packaged Windows x64 native addon, local NTFS/ReFS targets and runtimes, and Windows 10 or later. Native handles enforce path admission, private DACLs, and Job Object ownership automatically."\]

## relationship_coverage

null

## locations

\[\]

## evidence_links

\["ev_9f7562d3f4474d2cfe55dea288372081f47dbab495d4e9b1339c03eb408aa80e"\]

## caller_input_path

C&#58;\\Users\\Usuario\\AppData\\Local\\CapCut\\Apps\\9.8.0.4213\\CapCut.exe
