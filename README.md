# AutoCAD Polyline Vertices Coordinator

The AutoCAD Polyline Vertices Coordinator is a simple application designed to coordinate every vertex of specific polyline. 


![image](https://github.com/Alfredjank/AutoCAD_automation/assets/134058448/c95d366b-ac78-4bd7-b2a5-9474db75d2e8)



## How it works

- **Layer-specific Search:** The application scans the active AutoCAD drawing for polylines with a layer name '310_1proj' or '310_4proj'. You may freely change layer name in the code for your specific needs.

- **Vertex Coordinate Extraction:** Once the target polyline is identified, the application extracts coordinates for every vertex of the polyline.

- **Copy Coordinate Block:** In the drawing there must be coordinate block that application can copy and move to the needed points of polyline.
