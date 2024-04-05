# BIO CODE BREAKERS
## ML HACKATHON
### PROJECT: PROTEIN ENGINEERING

The diversity and significance of amino acid chains in various industries have led to the exploration of protein engineering techniques. This project aims to generate valid protein sequences using innovative approaches without relying on transformers, thereby leveraging unique methodologies rooted in NLP-based techniques.

#### PROTEIN ENGINEERING
The problem statement revolves around generating valid protein sequences from a limited set of examples. This endeavor resembles a GenAI task with potential applications in the pharmaceutical sector.

#### DATA ANALYSIS
Exploratory data analysis involves the examination of categorical and continuous data, with emphasis on plotting the distribution of protein sequence classes.

#### MY 'UNIQUE' METHODOLOGY
In tackling GenAI-based tasks, the conventional approach involves employing large parameter-based transformers. However, considering the complexity and cost implications, this project employs simple NLP-based techniques coupled with a novel Gen Algo model.

*PS: While acknowledging the intriguing prospects of Graph-Based DNNs like 'ProteinSolver,' this project prioritizes the development of a distinct methodology.*

#### APPROACH 1: FILL IN THE BLANKS
This approach involves randomly removing amino acid groups from protein chains and treating the resulting 'blanked' sequences as inputs, with the original amino acid chains serving as labels. A compact GRU-based architecture is utilized for efficient training on a small dataset of 1000 samples.

##### Example:
* Input Sequence: MMBNNB_MM
* Output Sequence: MMBNNBVM

#### APPROACH 2: PREVALENT PAIRS
This innovative technique focuses on identifying the most prevalent pairs of amino acids within protein sequences. By training a GRU-based Recurrent Neural Network using these prevalent pairs as inputs and the amino acid chains as outputs, the model can generate new protein chains corresponding to different amino acid pairs.

#### GITHUB REPO LINK
[GitHub Repository](#)

#### MATHEMATICAL ASPECT
While the model's scalability may be limited mathematically, its practical utility in day-to-day scenarios is notable.

#### FUTURE SCOPE
Integration with general Protein Solver models can enhance the breadth of results generated. Furthermore, with additional training time and data, such models could serve as efficient tools for graduate students seeking rapid and reliable results.
