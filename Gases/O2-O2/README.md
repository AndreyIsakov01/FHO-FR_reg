#FHO-FR_reg для O2-O2

Аппроксимационные формулы для O2-O2 представлены в общем виде:
$$k_\text{VT}^{i \to i-1} = \exp\left(a_0 + a_1 \cdot {T}^{-\frac{1}{3}} + \dots + a_4 \cdot {T}^{-\frac{4}{3}}\right),$$

где $a_0, ..., a_4$ - необходимые для аппроксимации значения, которые находятся в таблице - coefs_for_poly_FHO_FR_O2-O2.txt. В данной таблице стобцы записаны в порядке: $a_0, ..., a_4$, соответственно. В строке i находятся коэффициенты для аппроксимации, которая соответствует переходу с уровня i+1 на i.

В plots/APE представлены графики относительной ошибки, в зависимости от значения температуры T.  