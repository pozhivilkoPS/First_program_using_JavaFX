1)Группа состоит из элементов JTextField, JComboBox, JButton. Пользователь заносит текст в JTextField, затем нажимает элемент JButton, после чего текст из JTextField заносится в элемент JComboBox. Если вносимый текст уже существует в JComboBox, то при добавлении должно быть выведено диалоговое окно о невозможности добавления введенного текста. 

2)Группа состоит из элементов JTextField, JButton1, JButton2. Пользователь заносит текст в JTextField, затем нажимает элемент JButton1, после чего текст из JTextField отображается на элементе JButton2. При нажатии на JButton2 тексты на кнопках меняются местами. 

3)Группа состоит из элементов JTextField, JButton, JRadioButton1, JRadioButton2, JRadioButton3. Пользователь заносит имя одного из элементов типа JRadioButton в JTextField, затем нажимает элемент JButton, после чего соответствующий элемент помечается, причем со всех остальных пометки должны сниматься. При повторном нажатии на JButton метка с уже выделенного элемента JRadioButton не должна исчезать. Если введено имя JRadioButton, которого не существует, то должно быть выведено диалоговое окно с ошибкой. 

4)Группа состоит из элементов JTextField, JButton, JCheckBox1, JCheckBox2, JCheckBox3. Пользователь заносит имя одного из элементов JCheckBox в JTextField, затем нажимает элемент JButton, после чего соответствующий элемент помечается, если он не был помечен или с соответствующего элемента снимается метка, если он был помечен. Метки оставшихся двух компонент не должны менять свое состояние. Если введено имя JCheckBox, которого не существует, то должно быть выведено диалоговое окно с ошибкой. 

5)Группа состоит из элементов JTextField, JButton1, JButton2, JButton3, JTable. Элемент JTable содержит два столбца. Пользователь заносит текст в JTextField, затем нажимает элемент JButton1, после чего текст из JTextField заносится в первый столбец элемента JTable. Затем нажимает элемент JButton2, после чего выделенный текст из первого столбца JTable переноситься во второй столбец элемента JTable в той же строке, затем нажимает элемент JButton3, после чего выделенный текст из второго столбца JTable переносится в первый столбец элемента JTable в той же строке. В элементе управления JTable в каждой строке один столбец всегда остается пустым. Если выделенная для переноса ячейка содержит пустое значение, то при нажатии на соответствующий элемент JButton2 или JButton3, ничего не должно происходить.

6)Разукрасить фон 5 групп элементов в 5 различных цветов. Затем реализовать две горячие комбинации клавиш. Например, ctrl+R, ctrl+S. При нажатии на первую комбинацию(ctrl+R) цвета групп начинают по очереди меняться местами: 1-й становится 2-м, 2-й становится 3-м и т.д., последний становится 1-м. Смена цвета происходит с задержкой в 1 секунду. При нажатии второй комбинации клавиш(ctrl+S) описанный процесс останавливается в любой момент времени. Если повторно нажать вторую комбинацию (ctrl+R), то процесс продолжится с того места, где был остановлен.
