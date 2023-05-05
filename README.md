# Purpose

This repo exists only to reproduce a specific problem with rector.

## How to reproduce the problem

If you launch `vendor/bin/rector process`, it will make the constant in `ComputeMetricsEasy` `final`, which is wrong, because `ComputeMiles` overrides it. 
