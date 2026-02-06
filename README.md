# Remanufacturing Lab - "ScaleUpCycle"
In order to investigate what role local initiatives can play in closing 'their own material cycle' and, more importantly, how they can benefit from it through less waste, affordable products and meaningful work, several concrete things have been developed within this project. Firstly, a simple design tool that can be used in a social enterprise setting. By allowing 'customers' to design their own products from recycled materials, they become more aware of eco-impact and upcycles themselves have less waste. By choosing schoolchildren as their target group, Stichting Stunt in Delft has been given a new way to play a role in STEM and environmental education. Secondly, after evaluating previous initiatives from the 'precious plastics' community, a robust plate press has been developed and built to be able to produce these products in an accessible way, utilizing people distanced from the labor market. The press has been designed, parts sourced, and assembly is underway with a goal of operation in the coming weeks. In the collaboration between the Stunt Foundation, TheUpcycle and the researchers and students of The Hague University of Applied Sciences, suitable work processes for the target group and product families have been developed, which make it possible to use the new tools.

Access to a low-cost, robust plate press has been realized. The Plate Press 600 machine has been fully developed along with any necessities needed to fabricate it. The files will within shortly be made available through our webpage and/or GitHub and are still being shared with other interested parties in the Delft/The Hague region (including Circular Craft Center and ROC Mondriaan). They have been reviewed by an in-house team of mechanical experts from The Hague University of Applied Sciences, Mechanical Engineering Programme. The full engineering package will (after the last deployment test at Stichting Stunt) be shared through the Precious Plastics community.  

# General Overview
## File structure
In this repository you'll find the required documents to build your own plastic recycling press (purchase items, technical drawings, electrical scheme)

## Testing
**Design Choices and Adaptations 
Downsizing the Machine: The machine was downsized to fit Stunt's spatial and production abilities. 
Simplified Rib Structures: The top and bottom rib structures are the same grid design and use fewer parts for simplicity.   
Metal Sheet Hood Extractor: Sheet metal replaced the wood material of the extractor hood for improved safety as the machine heats up to high temperatures  
Electrical Box Positioning: The box is front-facing and positioned on the bottom frame to provide stability and easy access. 
Cable Arrangement: The electrical box cables were rerouted to exit the top and connect to the back of the plate press to accommodate the box's placement and the reduced space on the sides of the heat frames.  
Heating Blocks: The heating system was adjusted to 12 blocks instead of 24. The scaling down is not proportional to the scaling down of the heating plate, as the blocks are rectangular and must be spaced for equal heat distribution within the rib structure. 

**Main Challenges 
**
This is a challenging project that is not beginner friendly. It is costly and time intensive. Thankfully, the university's workshop, tool resources and highly skilled personnel were available.  
Reducing Plate Size: downsizing didn't mean reducing dimensions proportionally and required a redesign of many components.  
Extensive Welding: The project required extensive welding, and aligning and welding parts at precise angles without pre-made frames or structures was challenging. This required manual setup using standard clamps to hold everything in place. 
Dimension adjustments: Throughout this project, cutting and welding increased or decreased part and assembly dimensions. For example, an increase in the inner dimension of the heat frame meant an adjustment to the rib structure dimensions.  
Precision in Drilling: Accurate hole alignment is crucial for this project, especially in the frames. A drill press, in addition to experienced help, proved crucial for achieving precision.  
10mm Aluminum Plate: The aluminum heating plate was ordered in its exact dimensions as it is heavy and difficult to cut. However, the supplier was 1-2mm inaccurate. As such, the holes were made with a 1:1 template.  
Part Sourcing & Lead Times: Sourcing suppliers for all the components was challenging. Some aspects were missing from the Bill of Materials, and the potential for delayed shipping times must be considered when ordering parts. 
Heating Element: An ordering error of the heating elements required adjustments to the heating block dimensions. This caused a rework of the triangular rib structure to fit the rectangular heating blocks equally, leading to more components than initially planned. 
Multiple Skill Requirements: This highly technical project requires a mix of experienced mechanical, electrical, and welding skills. 
Plasma Cutting: We did not have access to a laser cutter suitable for metal, and custom outsourced parts can be costly. As a result, we used the in-house plasma cutter, which was less accurate and required fine-tuning of parts. 

**Tips and Tricks 
**
Pre-built Electrical Box with Door: Saves time and effort; inner components are more accessible  
Electrical Box Placement: Rest on the bottom frame for support and front-facing for better access.  
Dremel for Square Holes: Effective for cutting clean square holes for the front of the electrical box.  
Larger Cable Gland (M25): Easier cable routing. 
Sheet Metal for Hood: Sheet metal is used for the extraction hood for improved safety due to high temperatures.  
Standard Size Sheet: Order a standard 100mm x 6mm x 6000mm sheet to reduce the cutting required for rib structure parts.  
Deburring Tool: Helpful for smoothing sharp edges and post-drilling. 
Step Drill Bit: Useful for making larger holes in the frame and for cable gland openings. 
SolidWorks or Fusion 360: Use one or the other for simplicity and file transferring. Fusion 360 allows cloud collaboration, working on the same document, and storing files.  
1:1 Templates: Printing life sized templates for holes in the heat plates saved significant time in marking and drilling. 
Avoid Plasma Cutting for Threaded Holes: Plasma cutting hardens the material, making threading difficult.  
Cable Glands Installation: Install cable glands before welding to avoid complications later in the assembly. 

### Version control
A [Git Policy](docs/policy.md) was written for this project. Please adhere to it as tightly as possible during development.

### Documentation




# Attribution

- Project manager: [Manager of the project/project leader])
- Collaborator - "roles of the collaborator": [Name]
