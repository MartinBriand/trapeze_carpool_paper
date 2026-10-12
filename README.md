# Paper

Economics of High Occupancy Committed Lanes

# Authors

Martin Briand$^{a, *}$, Nicolas Coulombel$^a$, Guillaume Monchambert$^b$

$^{a}$LVMT, ENPC, Institut Polytechnique de Paris, Univ Gustave Eiffel, Marne-la-Vallée, France\
$^{b}$LAET, University of Lyon, Université Lyon 2, Lyon, F69007, France\
$^{*}$Martin Briand is the corresponding author. His corresponding email is [martin.briand@enpc.fr](mailto:martin.briand23@gmail.com).

# Note to readers

The tag publication_1.0.0 is the first for publication, the one used for the reviewing process. If the final published paper refers to this tag, it means that no modification has been required by the reviewing process. If the final publication links to another version, please use the one of the paper.

In the notebooks, you will see many codes that generate graphs that are not in the final paper. These are artefacts of the research process, we explore tracks that are not included in the final paper. Some explorations were mathematical only, and are therefore not in this code. We decided to keep only explorations which could be of interest for future research, others were deleted. Among others, you will find:

* Explorations on limits for $N \to 0^{+}$ (in `paper_visuals.ipynb`)
* A surface of the optimal allocation (in `solving_routine.ipynb`)
* A map of the equilibrium for any set of parameters. For the moment it is only 10×10 to avoid too long calculations, but you can make it larger if you are ready to wait (in `solving_routine.ipynb`)
* A solver when $\varphi$ is made varying for joint optimization. The code does not work anymore, but it did in the past. With a little effort (or AI), you should get it work.

All of this may seem usable but dirty. The fact is that 100% of the code was written by hand, and 95% of the proofs were human brain. (This is a late publication of an old work that was done before AI ruined the process of human research by providing correct solutions with much less effort). We are sorry for that very old 2024 standard.

# Note to users

For Python package management, we use the *absolutely fantastic* `uv` tool. The user is invited to read the documentation of the tool online and use it.

To init the environment, once `uv` has been installed, run `uv sync`. Then the `.venv` folder should be created and populated with the exact same libraries as those used by the author (thus no version headaches).

Your code editor should automatically detect the environment and use it. If you prefer to use Jupyter Lab to edit code, run `uv run jupyter lab`.

You should also create an `output/` directory at the root of the repository. The code will generate and save graphs in this directory.

# Note to contributors

If you want to contribute, please refer to the README.md of the main branch