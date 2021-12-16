# hse21_hw3


Сравнение RNA-seq данных перепрограммированных SRR3414629, SRR3414630, SRR3414631 и неперепрограммированных (контрольных) мышиных эмбриональных фибробластов (MEFs) SRR3414635, SRR3414636, SRR3414637 и нахождение генов, которые наиболее сильно изменяют свою экспрессию в этом процессе.

# Ссылки: 

Часть 1. https://colab.research.google.com/drive/1uUmuccZWHds2y0AQM_iK6ydsE-kfpfJk?usp=sharing

Часть 2. 

# Скриншоты и статистика из файлов multiQC

![image](https://user-images.githubusercontent.com/93263861/146330211-1e98bf4b-ae17-43a8-a279-5b77728940f6.png)

![image](https://user-images.githubusercontent.com/93263861/146330640-7536db91-b142-42e4-8643-a9240f924b2b.png)

![image](https://user-images.githubusercontent.com/93263861/146330752-dfdf1064-8633-42d7-9ccd-2ab089e2355a.png)

![image](https://user-images.githubusercontent.com/93263861/146330791-72f495f5-586f-4da1-9654-c9c04b5b0fe7.png)

![image](https://user-images.githubusercontent.com/93263861/146331774-3e7201bf-10ee-48f7-955f-a69db182cd1b.png)

![image](https://user-images.githubusercontent.com/93263861/146331826-fb7f2f7c-8d27-4358-8aff-6758fba641b9.png)

![image](https://user-images.githubusercontent.com/93263861/146331871-0cc85967-f2f7-41cd-8c3c-d1b39918a584.png)

![image](https://user-images.githubusercontent.com/93263861/146331957-3d2d4610-b16b-494e-b812-159f6ed0406a.png)

# Таблица со статистикой

![image](https://user-images.githubusercontent.com/93263861/146333421-13978bcf-77fa-4d86-b55c-1c149d8c9b87.png)

# Сводная таблица ALL.counts, указано кол-во чтений уникально картированных на каждый ген в каждом образце:

![image](https://user-images.githubusercontent.com/93263861/146333829-358956fd-679c-4297-968d-8ce3271f9497.png)

# Дополнительная таблица с информацией

![image](https://user-images.githubusercontent.com/93263861/146333975-25b282f5-bf23-4df3-b558-e734c9357087.png)

# Подсчёт данных для таблиц:

![image](https://user-images.githubusercontent.com/93263861/146334561-53bbfa2d-964d-4e41-bed9-05f116cb5888.png)

![image](https://user-images.githubusercontent.com/93263861/146334736-3b422bea-091d-4456-97db-82f6394b2f66.png)

![image](https://user-images.githubusercontent.com/93263861/146334775-b2bdd501-035b-48d6-94a0-6516837a3e07.png)

![image](https://user-images.githubusercontent.com/93263861/146334865-f45b270a-7960-46c5-ac25-468c48e9b117.png)


# Графики из анализа DESeq2

1) MA-plot, показывающий Log2FC для генов:

![image](https://user-images.githubusercontent.com/93263861/146364782-5c0156d4-cf36-446f-b0f3-7b9c4b2866c2.png)

2) Тепловая карта показывает, что все контрольные образцы похожи между собой и все перепрограмированные образцы похожи между собой, а образцы контроля отличаются от образцов эксперимента.

![image](https://user-images.githubusercontent.com/93263861/146363579-2bd81b06-08c2-487f-9848-f7fa13e6f4e3.png)

3) График разниц экспрессий для 20 наиболее дифференциально экспрессированных генов.
 Так, для первой строчки, в контроле ген сильно экспрессировался (красный цвет), а в эксперименте его экспрессия упала (оранжевый цвет). Значения обозначены цветами:

![image](https://user-images.githubusercontent.com/93263861/146363748-4bcbd84b-abff-4d18-8fd1-10f0e66ce856.png)

4)  Графики со значениями "Normalized counts" в контрольных и перепрограммированных образцах для генов, которые наиболее значимо поменяли свою экспрессию:


![image](https://user-images.githubusercontent.com/93263861/146364232-e1de1c08-d486-4522-8ead-b847e45865be.png)


![image](https://user-images.githubusercontent.com/93263861/146364253-8b74efc6-f040-436d-9227-0a7786f34513.png)


![image](https://user-images.githubusercontent.com/93263861/146364296-d966735b-7a87-4af4-bf63-4c0af7990a51.png)


![image](https://user-images.githubusercontent.com/93263861/146364339-5e40ecd0-1275-48c6-b435-4dddcf6e7258.png)


 ![image](https://user-images.githubusercontent.com/93263861/146364369-ddb9baf6-032f-49fb-9ae2-00da72d31402.png)


