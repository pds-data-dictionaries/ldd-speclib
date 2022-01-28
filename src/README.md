# LDD Source Directory

SPECLIB Discipline Dictionary Revisions:

4/21/2020, version 1000
- GEO/SHS Post-peer-review release

10/8/2020, version 1100
- GEO/SHS Used DD_Associate_External_Class to define Internal_Reference
- GEO/SHS Changed attribute names:
        spectral_range_unit -> spectral_range_unit_name
        spectral_sampling_interval_unit -> spectral_sampling_interval_unit_name
        spectral_resolution_width_unit -> spectral_resolution_width_unit_name

11/20/2020 version 1200
- GEO/SVB Revised to incorporate Raman spectra

12/16/2020 version 1210
- GEO/JGW Revised to incorporate XAS glass spectra

4/26/2021 version 1212
- GEO/JGW Added specimen_thin_section_flag to Specimen_Parameters

7/16/2021 version 1212
- GEO/SHS Changed definition of Internal_Reference in Ancillary_Product and Measurement_Instrument classes,
       using DD_Association instead of DD_Associate_External_Class. Corrected rules to validate the reference_type.
- GEO/SHS Rebuilt for PDS IM 1G00

8/2/2021 version 1300
- GEO/JGW Added permissible value Natural-Doped for material_origin
- GEO/JGW Added attributes to Measurement_Parameters class

12/16/2021 version 1300
- GEO/SHS Revised to use PDS IM 1.17.0.0. No other changes.

01/28/2022 version 1300
- GEO/SHS Revised readme.md files for GitHub. No changes to dictionary.
-----
This directory should contain one IngestLDD for the LDD being built. The auto-generation script does not currently support multiple versions of an LDD being maintained.

See the [tutorial on updating and building an IngestLDD](https://pds-data-dictionaries.github.io/support/tutorials.html#ldd-update-and-build-tutorial) and the [LDD Update Process](https://pds-data-dictionaries.github.io/development/ldd-update.html) for more details.
