# Custom BOM columns

Panel **Bill of Materials** ‣ **Custom Columns**. Up to 5 columns between Part and Qty, on the drawing, in the annex and in the
CSV / Excel files.

1. Click **+** and choose the **Source**:
   - **Material**: material slots of the part;
   - **Size**: overall size, largest first, in the drawing units;
   - **Collection**: the collection of the part;
   - **Position**: world coordinate on axis X, Y, Z or all three, at the min edge, centre, max edge or origin;
   - **Custom Property**: any property of the objects, read on the object then on its mesh (e.g. Supplier or Reference).
2. Change the **Title** if needed; the arrows set the order of the columns.
3. Make Plan as usual. Bill of Materials ‣ **Count by** must not be None.

When the parts of a row have different values, they are listed (« steel, alu », « … » beyond two).
