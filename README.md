# obfusCKate fork

A fork of obfusCKate, designed to be easier to make compatibility patches for.

Changes:

- skills are displayed via customloc instead of datafunctions, which makes them more readable and also more resuable by total conversions
- refactored the vanilla GUI files so they're easier to patch when a new CK3 update comes out
- moved some GUI elements to a separate file so they don't clog up vanilla files
- cleaned up the error log somewhat

Relevant files:

- `common\script_values\obf_core_values.txt`: definition of skill + opinion values
- `common\customizable_localization\obf_core_customloc.txt`: display of those values
- `gui\shared\obf_types.gui`: moved GUI elements
- there are some new macros at the end of `data_binding\obf_macros.txt`