Тест
====

У овом фајлу биће приказано неколико питања која вам могу послужити као мустра за прављење тестова. 


Ово је пример питања где је потребно да ученик изабере један тачан одговор. Обратите пажњу на формат питања. Прво идее наслов питања који је подвучен знаком "~", након тога следи директива за укључивање абц питања ``mchoice`` - обратите пажњу на форматирање (две тачке на почетку за нову директиву, две тачке након тога, јединствен id директиве, увлачење за све одговоре, обавезно обележвање тачног одговора". Након тога следи текст питња и након тога следи директива за укључивање кода 


Питање 1.
~~~~~~~~~

.. mchoice:: izrazi_zbir_dva_broja
    :answer_a: 19 + 26
    :feedback_a: Нетачно    
    :answer_b: 45
    :feedback_b: Тачно
    :answer_c: Пајтон окружење ће исписати поруку о грешци.
    :feedback_c: Нетачно    
    :correct: b

    Шта ће исписати Пајтон окружење када му у командну линију унесеш следећи израз? Изабери тачан одговор:

    .. code-block:: python

     19 + 26




Следеће питање је пример за случај у коме директива за питање са више понуђених одговора има неколико тачних одговора. 


Питање 2.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. mchoice:: izrazi_zabelezi_izraz_1_1
    :multiple_answers:
    :answer_a: 26 : ( 25 + 70 )
    :feedback_a: Нетачно    
    :answer_b: ( 45 - 26 ) ( 25 - 70 )
    :feedback_b: Нетачно    
    :answer_c: 26 * 25 * ( 45 - 25 )
    :feedback_c: Тачно
    :answer_d: 45 - 26 * - 25 - 70
    :feedback_d: Тачно
    :answer_e: 45 - [(26 + 25) - 70]
    :feedback_e: Нетачно    
    :correct: c,d


    Који од понуђених израза представљају исправно записане Пајтон изразе? Изабери тачан одговор:


Следеће питање је пример за питање у коме се од ученика очекује да допише одговор. Обратите пажњу на форматирање тачних и нетачних одговора 

Питање 3.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. fillintheblank:: izrazi_citanje

    Шта ће исписати Пајтон окружење када изврши следећи програм?

    .. code-block:: python

     d = 0
     n = 3 * d
     print(n)

    Одговор: |blank|

   - :^\s*0\s*$: Тачно
     :x: Одговор није тачан.


Следеће питање може послужити као пример за укључивање слике у питање. Обратите пажњу на поравнање и на синтаксу за укључивање слике. 

Питање 4.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


.. mchoice:: karel_dve_petlje
    :answer_a: Програм (1)
    :feedback_a: Нетачно    
    :answer_b: Програм (2)
    :feedback_b: Нетачно    
    :answer_c: Програм (3)
    :feedback_c: Нетачно    
    :answer_d: Програм (4)
    :feedback_d: Тачно
    :correct: d
    

Питање 5.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. clickablearea:: question1
   :question: Click the rainbow color(s)
   :iscode:

   :click-correct:Red:endclick:
   :click-incorrect:Gold:endclick:
   :click-correct:Blue:endclick:
   :click-incorrect:Black:endclick:



Питање 6.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


.. clickablearea:: question2
   :question: Click the rainbow color(s)
   :table:
   :correct: 1,0;2,2;3,1;3,3;4,2
   :incorrect: 2,1;2,3;3,2;4,1;4,3

   +-------+---------+--------+
   |  Red  |  Orange | Yellow |
   +-------+---------+--------+
   | White |  Green  | White  |
   +-------+---------+--------+
   |  Blue |  White  | Indigo |
   +-------+---------+--------+
   | White |  Violet | White  |
   +-------+---------+--------+


Питање 7.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


   .. fillintheblank:: unique_id

   + --- Content area ---
   |
   | A question or prompt with 0 or more lines of content
   |
   | followed by a list
   | One bullet list item for each blank to be rendered.
   |
   + --------------------


Питање 8.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. fillintheblank:: unique_id

   Question text goes here, with at least one |blank|, more are added like this: |blank|.

   - :answer: Feedback for blank 1
     :x: The last item of feedback mathes anything, regardless of content
   - :another: Feedback for the second blank
     :yet more: Feedback
     :.*: A wildcard for the second blank


Питање 9.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. fillintheblank:: fitb-ex1
   :casei:

   Fill in the blanks to make the following sentence: "The red car drove away."

   The ``|blank|`` car drove ``|blank|``.

   -   :red: Correct.
       :x: Incorrect. Try 'red'.
   -   :away: Correct.
       :x: Incorrect. Try 'away'.



Питање 10.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

       .. parsonsprob:: unique_id
   :options:

   + --- Content area ---
   |
   | one or more lines of instruction for the problem
   | -----
   | one or more lines of text
   | =====
   | grouped by
   | =====
   | five equals
   |
   + --------------------



Питање 11.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


   .. parsonsprob:: pa-ex1

   Construct a block of code that correctly implements 
   the <b>accumulator</b> pattern.
   -----
   x = 0
   for i in range(10):
       x = x + 1



Питање 12.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

       .. parsonsprob:: par_ex_num_left
   :numbered: left

   Construct a function that returns the max value from a list.
   -----
   def findmax(alist):
   =====
       if len(alist) == 0:
           return None
   =====
       curmax = alist[0]
       for item in alist:
   =====
           if item > curmax:
   =====
               curmax = item
   =====
       return curmax


