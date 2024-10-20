# macOSDorkingSystem

late List<T> _items;  /*list to ICONS*/
int? _draggedIndex;   /*getting DRAGGED_ITEM INDEX*/

_onDragStarted(int index) => /*method to get the INDEX of item that user wants to DRAG*/
_onDragEnded() => /*method to get the INDEX of item that user wants to STOP*/

DragTarget => /*widget to recieve the DRAGGED_ELEMENT index*/
Draggable => /*STARTING, ENDING, the particular element/icon/index DRAGGING*/

_buildIcon(T icon, double size, {bool isDragging = false}) => /*method returns widget user to ANIMATE and FADE the DRAGGING INDEX*/
