---
layout: exercise
title: Databases - Structure 1
---

The Plots table in our version of the Portal database violates one of
the major rules of database structure (the whole gosh dang table is
redundant for Pete's sake!). Figure out a better design using one table
to link each plot number to a single experiemental code (save this as
**Plots - Single Code**) and a second table that includes various
versions of each type of code (save this as **Experiments**). It is
probably easiest to restructure the table by hand in a spreadsheet and
then import the new tables into Access, but if you're feeling bold you
could do the restructuring using Python.

Using your new plot related tables write a query that determines the
Plot Type Description and the number of plots of each type. Save this as
**Number of Plots by Treatment**.
