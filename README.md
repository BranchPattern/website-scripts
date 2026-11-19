# website-scripts

Front-end JavaScript loaded by branchpattern.com. Both files were originally written by Antenna for the BranchPattern website and copied here unchanged so the site no longer depends on an outside account. Full-history backups of Antenna's source repositories are kept privately in this organisation (antenna-branchpattern-backup, antenna-bp-risk-estimator-backup).

| File | Used on | Copied from |
|---|---|---|
| `scripts.js` | every page (Webflow Site settings > Custom code > Footer code): animations, smooth scrolling, project map, team grid, navigation effects | Antenna-Digital/branchpattern, commit 4080ceb |
| `estimator/bundle.js` | Facility Infection Risk Estimator page only (page settings > head code): the estimator calculations | Antenna-Digital/bp-risk-estimator, commit cf5fc35, built file dist/bundle.js |

The site loads these files through jsDelivr, pinned to a full commit of this repository, for example:

    https://cdn.jsdelivr.net/gh/BranchPattern/website-scripts@<commit>/scripts.js

To change a file: edit it here, commit, then put the new commit in the Webflow code and republish. A pinned commit never changes, so nothing here needs routine maintenance.
