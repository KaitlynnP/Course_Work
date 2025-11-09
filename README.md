# Course_Work
Selection of programs created for course work.

Code available by request from employers.

# Dynamic Convex Hull Builder (Java)
Developed a HullBuilder class implementing dynamic algorithms to maintain and update the convex hull of a 2D point set as points are added. Designed and coded three core methods (addPoint, getHull, isInsideHull) to efficiently construct, query, and test point containment within the hull. Ensured algorithmic correctness through rigorous testing and formal reasoning, then optimized for asymptotic efficiency under worst-case performance. Utilized computational geometry techniques such as orientation (chirality) tests to guarantee accurate convex hull construction during dynamic updates.

Key Skills: Java, computational geometry, algorithm design and analysis, asymptotic complexity, data structure optimization, software testing

# Red-Black Tree Implementation (Java)
Implemented efficient Find and Insert operations for a Left-Leaning Red-Black Tree to maintain balanced structure and logarithmic height. Designed insertion logic involving rotations and color flips to preserve red-black tree properties after each update. Verified correctness and performance through automated testing, achieving Θ(log n) runtime for both search and insertion.

Key Skills: Java, data structures, algorithm design and analysis, tree balancing, asymptotic complexity

# Image Graph Processing and Flood Fill Implementation (Java)
Implemented a graph-based image processing system where each pixel is represented as a vertex in a PixelGraph data structure. Developed classes (PixelGraph, PixelVertex) to model pixel adjacency and connectivity, and implemented key traversal algorithms (FloodFill (DFS and BFS), OutlineRegion (DFS and BFS), and CountComponents) to perform image segmentation and region analysis. Integrated with a graphical image viewer to visualize and test results on real images. Focused on efficient graph traversal, data structure design, and algorithmic correctness.

Key Skills: Java, graph algorithms, BFS/DFS traversal, image processing, data structures, algorithm implementation, software debugging and visualization

# Move-To-Front (MTF) Encoder/Decoder Implementations (C & Python) 
Designed and implemented four Move-To-Front (MTF) encoder/decoder programs in both C and Python, progressively building functionality.

Developed C programs using dynamic memory allocation and separate compilation, allowing runtime adaptability to input size, efficient dynamic word list management, and modular code for encoding and decoding while eliminating global variables. Ensured Linux platform reliability and correctness of MTF decoding against provided test files. 

Developed Python 3 programs using a module-based architecture, supporting larger dictionaries, multi-character codes, and validating multiple MTF magic numbers, while maintaining backward compatibility with previous MTF file formats. Performed automated testing with provided test cases using custom Unix scripts to ensure correctness and reliability.

Key Skills: C, Python 3, MTF encoding/decoding, dynamic memory, file I/O, procedural programming, modular programming, Unix utilities (diff, cmp, hexdump), software testing, git version control, cross-platform code reliability

# Simple Shell Interpreter (SSI) Implementation (C)
Designed and implemented a simplified Unix shell (SSI) in C supporting foreground and background program execution, directory navigation, and signal handling. Developed robust command parsing using readline() and strtok(), enabling execution of arbitrary commands with multiple arguments. Implemented built-in commands such as cd for directory management, supporting relative, absolute, and home paths. Enabled background execution with job tracking (bg, bglist) and automatic termination notifications using fork(), execvp(), and waitpid() with WNOHANG. Ensured proper handling of Ctrl-C signals to terminate only foreground processes without exiting the shell. Tested extensively on UVic Linux server for correctness and reliability.

Key Skills: C, Linux system calls, signal handling (SIGINT), background process management, command-line parsing, modular code design, software testing, Unix utilities, git version control
