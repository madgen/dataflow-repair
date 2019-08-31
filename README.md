# Dataflow repair for Datalog in Datalog

Datalog programs may have range restriction (all head variables appearing in the
body) and mode (sufficient instantiation of variables) errors. These can sometimes
be fixed by a dataflow aware program transformation.

This repository contains a [MetaDL](https://github.com/lu-cs-sde/metadl)
implementation of the dataflow analysis necessary for this repairing transformation.
