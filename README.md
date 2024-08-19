# NiceDrivers
this repo holds some drivers im planning/working on/finished. these are made for 22H2 for when specific offsets are required.

# drivers im working on/planning:
- minifilter driver for protecting the system:
1) read hook to protect from disclosed information disclosure both in file access and in sensitive content. also worked
   on irreversible conversion of data to prevent read (can be improved for specific uses)
2) write/cleanup/create protections (FINISHED)

- ETW driver to protect the system and log different events like context switches or file operations (FUTURE)
- ETW driver to attack the mechanism as some sort of virus (FUTURE)
- Type-2 hypervisor to protect the system (FUTURE)
- Type-2 hypervisor to use EPT hooking for an all-around hooking system for all valuable hooks possible (FUTURE)
