# GnomeSort

The gnome sort 

This sorting algorithm similar to the method the inserts, but in this case, the moving elements on their positions is performed by swapping two adjacent elements in the same way as a bubble. The gnome sort is extremely simple and does not need nested loops. The average time of order is O(n^2), but if the original data is almost in order, time is close to O(n). In practice, this algorithm runs as fast as a method of "inserts".

Consider the algorithm finds the first two elements, which are arranged in the wrong order, and swaps them. The principle of the gnome sort is built on the fact that changing two elements of the array places the wrong order of items we can get only after or immediately before changing elements. The algorithm assumes that the data after the current position is ordered, therefore it is enough to check only the position immediately before the two current elements.

Гномья сортировка. 

Этот алгоритм сортировки схож с методом вставок, только в этом случае перемещение элементов на их позиции производится путем перестановки двух соседних элементов, аналогично методу "пузырька". Гномья сортировка весьма проста и для нее не требуется вложенных циклов. Среднее время упорядочивания равно O(n^2), но если изначально данные и так практически находятся в нужном порядке, то время становится близким к O(n). На практике данный алгоритм выполняется также быстро как и метод "вставок".

Рассматриваемый алгоритм находит первые два элемента, которые расположены в неправильном порядке, и меняет их местами. Принцип гномьей сортировки построен на том факте, что меняя два элемента массива местами, неправильный порядок элементов мы можем получить только после или же непосредственно перед меняемыми элементами. Алгоритм не предполагает, что данные после текущей позиции упорядочены, следовательно достаточно проверять только позицию непосредственно перед двумя текущими элементами.
