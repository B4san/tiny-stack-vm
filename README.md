# tiny-stack-vm entry

A faithful interpreter of make.fun's tiny stack ISA (see the kit's
`program/generator/subject/ISA.md`): 32-bit wrapping arithmetic, a 256-value data
stack, 64 return addresses, 256 words of memory, input/output, and all ten traps
with their exact exit codes, plus the step and output limits.

Run it on the practice set with the kit's grader:

```
node tiny-stack-vm-01-run-20261122-kit/cli/makefun.mjs grade-local --kit tiny-stack-vm-01-run-20261122-kit --bot entry --driver process
```

MIT licensed (see LICENSE).
