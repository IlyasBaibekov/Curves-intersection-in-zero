# Curves-intersection-in-zero
Код на Python. Алгоритм нахождения кратности пересечения в точке (0,0)

Кратность пересечения - важный параметр при изучении кривых. Например, у двух прямых кратность единица. У параболы y = x^2 и прямой y = 0 - кратность пересечения равна двум.

Существует алгоритм, который с легкостью находит кратность пересечения в начале координат. Его реализация - в ноутбуке. 

Ограничения: реализация алгоритма не терпит дробей, поэтому все дробные коэффициенты записывайте в целом виде (кривая задается соотношением An x^n + An-1 x^(n-1) ... = 0)
От иррациональности, к сожалению, не всегда получится избавиться, но вы можете записать иррациональное число приближенно в виде дроби, а далее избавиться от дробных коэффициентов. В подавляющем большинстве случаев это не изменит ответа на задачу.

