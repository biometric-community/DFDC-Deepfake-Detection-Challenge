        # DFDC

        [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
        [![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FDFDC--Deepfake--Detection--Challenge-181717?logo=github)](https://github.com/biometric-community/DFDC-Deepfake-Detection-Challenge)
        [![Access: public](https://img.shields.io/badge/access-public-0e8a16.svg)](https://ai.meta.com/datasets/dfdc/)

        **DFDC** (Deepfake Detection Challenge) — large-scale deepfake video benchmark from Meta.

        - **Dataset repository**: https://github.com/biometric-community/DFDC-Deepfake-Detection-Challenge
        - **Upstream source**: https://ai.meta.com/datasets/dfdc/
        - **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
        - **License (data)**: upstream terms — this packaging does **not** relicense the data


        | Field | Value |
        |-------|-------|
        | Catalog id (tbiom) | `dfdc` |
        | Category | `deepfake` |
        | Access | `public` |
        | Upstream homepage | https://ai.meta.com/datasets/dfdc/ |

        ## TL;DR

        - **Task**: deepfake / face-manipulation detection
        - **Access**: **public**
        - **This mirror**: documentation + download helpers only (no bulk payload in git)
        - **Notes**: Free with Meta terms; multi-hundred-GB AWS download. This mirror ships docs/helpers only — do not mirror full videos here.

        ## Table of contents

        - [Download](#download)
        - [Dataset structure](#dataset-structure)
        - [Known issues and caveats](#known-issues-and-caveats)
        - [License](#license)
        - [Citation](#citation)
        - [Contact](#contact)

        ## Download

        ### Clone this repository

        ```bash
        git clone git@github.com:biometric-community/DFDC-Deepfake-Detection-Challenge.git
        cd DFDC-Deepfake-Detection-Challenge
        ```

        ### tbiom monorepo helper

        ```bash
        bash projects/datasets/scripts/download_dfdc.sh
        ```

        Then follow the printed upstream steps and place archives under `projects/datasets/dfdc/`.

        ## Dataset structure

        ```text
        DFDC-Deepfake-Detection-Challenge/
        ├── README.md
        ├── LICENSE                 # helpers / docs (CC BY 4.0)
        ├── .gitignore
        └── extracted/              # local only after you download (gitignored)
        ```

        ## Known issues and caveats

        - Upstream hosts / Drive quotas often block fully automated downloads.
        - Do not commit multi-GB payloads to this GitHub mirror.

        ## License

        Helpers/docs: CC BY 4.0. Dataset files: upstream license / access agreement.

        ## Citation

        ```bibtex
        @article{dolhansky2020dfdc,
  title={The DeepFake Detection Challenge (DFDC) Dataset},
  author={Dolhansky, Brian and others},
  journal={arXiv:2006.07397},
  year={2020}
}
        ```

        ## Contact

        - Upstream: https://ai.meta.com/datasets/dfdc/
        - Packaging: https://github.com/biometric-community/DFDC-Deepfake-Detection-Challenge/issues
