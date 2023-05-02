Download Link: https://assignmentchef.com/product/solved-cosc363-assignment1-opengl-museum
<br>
In this assignment, you will develop a graphics application to display your version of an <strong>OpenGL Museum</strong> that houses a few interesting exhibits created using OpenGL models. The assignment task can be broadly divided into four sections:

Minimum requirements (10 marks):  The scene should contain a set of minimum features as outlined in Section 2.

Extra features (5 marks):  You can implement a set of extra features and gain up to a maximum of 5 marks. A few examples of such features are given in Section 3.

Rendering quality (3 marks):  Up to 3 marks are allocated for the overall rendering quality of the scene, including animations (Section 4).

Report (2 marks):  You should also prepare a brief report containing a few screenshots and a description of the scene  (see Section 5).

<h1>2.  Minimum Requirements</h1>

2.1  When the program is run, the opening scene should display a model of the museum building. This need not be a highly complex model. It could be constructed using a set of polygonal primitives, GLUT objects or surface design methods (see Section 6). The building should have an entrance into the interior where the models are displayed.

2.2  In the opening scene, the viewer must be able to navigate the camera using arrow keys to the interior of the building. The up and down arrow keys must move the camera forward and backward respectively, the left arrow key should change the direction of motion towards left by a certain angle, and the right arrow key should change the direction of motion towards right. You may define additional functions for processing keyboard, special key, and mouse inputs as needed.  Please do not use passive mouse motion function. The initial camera position must be somewhere outside the museum entrance.

2.3  Inside the building, there must be <em>at least three</em> “museum exhibits”. At least two of the models must display some animation (either initiated by a key press, or a continuous animation). Simple transformation sequences (e.g. a constant rotation about an axis) will not be counted as animations.

2.4   At least three different textures must be used in the scene. It is not necessary to texture map all surfaces.  Please do not use very large images (&gt;10MB) as textures.

<h1>3.  Extra Features and Marks</h1>

A list of possible features, and the approximate marks they would each gain if implemented correctly (subject to a maximum of 5 marks) are given below.

<ul>

 <li>Planar shadows cast by at least one object (1 mark)</li>

 <li>A spot light on a moving/rotating object (1 mark). The movement of the spotlight should be clearly visible.</li>

 <li>Physics based (e.g. gravity) animation. Give relevant equations in your report. (12 marks depending on the complexity of the Physics model)</li>

 <li>A surface shape generated using a mathematical formula (e.g. paraboloids) or a complex design process. Please provide sufficient details in the report. (1-3 marks depending on the complexity of the model)</li>

 <li>Collision detection (1 mark)</li>

 <li>Sky box (1 mark)</li>

 <li>Particle systems (1-2 marks depending on the complexity of the model)</li>

</ul>

The marks associated with each feature should be taken to be indicative of the time and/or effort required to implement that feature. The list given above should not be taken as the complete set of features that can be implemented.

<h1>4.  Rendering Quality</h1>

In the context of this assignment, rendering quality refers to the visual aesthetic quality of the models and animations displayed by the program. For example, slow and jittery animations, incorrectly rendered sky boxes and shadows, and improper illumination may cause marks to be deducted for poor rendering quality.

<h1>5.  Report (Max. marks: 2,  Max. number of pages: 4)</h1>

The report should include the following sections:

<ul>

 <li>Your name and student number.</li>

 <li>A brief description (1 paragraph each) of each model, including any diagrams, sketches etc. used in the design of the models.</li>

 <li>At least two screenshots showing important aspects of the scene or animations.</li>

 <li>A brief description of each extra feature implemented, including relevant equations.</li>

 <li>A full list of control functions (keyboard, mouse, special keys) defined for interacting with the scene.</li>

 <li>References to sources of textures, algorithms, equations etc., used in your work.</li>

</ul>

You may include more than 4 pages in the report, only if absolutely necessary. Please submit your report as a single <strong>PDF</strong> file.

<h1>6.  Models and Animations</h1>

The object models in the scene may be constructed using any of the following methods:

<ul>

 <li>By transforming and combining a set of (at least three) GLUT/GLU objects such as spheres, cubes, cylinders etc. to form a composite model.</li>

 <li>By using a set of polygonal surfaces comprising of quads and triangles.</li>

 <li>By using surface generation methods such as sweep surfaces, surfaces of revolution etc.</li>

</ul>

You are not required to design or use highly complex mesh models for this assignment. Designing objects using modeling packages such as Max, Blender, Lightwave, etc., will not give you any extra points.  Downloading pre-built mesh models from the Internet and using them in the program will also not give you any marks.

You may use parts of lab code and resources (models, images, image loading functions).  Models and animations developed in the lab will give you marks only if significant changes or enhancements have been made to them.

<ol start="7">

 <li><u> Program Development:</u></li>

</ol>

<ul>

 <li>Please do not use source codes of programs from online repositories, tutorials, and books.</li>

 <li>Develop your program in C/C++ language using only OpenGL 2 API. Please do not use OpenGL 4 code (vertex/fragment shaders etc.), or extensions (e.g. ARB, EXT etc.) that are not part of the standard OpenGL API.</li>

</ul>