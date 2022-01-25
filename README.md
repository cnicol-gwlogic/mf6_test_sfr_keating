# mf6_test_sfr_keating
MODFLOW 6 test of SFR leakage via dry cells using NEWTON 
(upstream weighting) flow option. 
Uses [USGS' Keating example](https://modflow6-examples.readthedocs.io/en/latest/_examples/ex-gwt-keating.html) [(notebook here)](https://github.com/MODFLOW-USGS/modflow6-examples/blob/master/notebooks/ex-gwt-keating.ipynb) as a basis, but replaces the 
Recharge (RCH6) package with the Stream Flow Routing (SFR6)
package. Keating's total RCH mass and water flux volumes are preserved.
