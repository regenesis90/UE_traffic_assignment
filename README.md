# Traffic Assignment by Frank-Wolfe Algorithm
* Find traffic assignment value at User Equilibrium, by FWA.
## Shortest Path Algorithm
* **`SPA_Dijkstra_ver1.ipynb`** : Dijkstra Method, ver.1
* **`SPA_Dijkstra_ver2.ipynb`** : Dijkstra Method, ver.2
* **`SPA_Moore_ver1.ipynb`** : Moore Method, ver.1

## Frank-Wolfe Algorithm
* **`UE_Frank_Wolfe_Algorithm_Tutorial.ipynb`** : Frank-Wolfe Algorithm, Step by Step Tutorial
* **`UE_Frank_wolfe_Algorithm_RUN.ipynb`** : RUN Frank-Wolfe Algorithm with Dijkstra(ver.2)

## Result
### Link Travel Volume at UE
|Link_num|O|D|x_n|Cost|
|---|---|---|---|---|
|1|1	|2	|4004.328254	|6.00051422|
|2|1	|3	|6973.989	|4.004731023|
|3	|2	|1	|3980.266057	|6.000501971|
|4	|2	|6	|5739.247095	|6.346453854|
|5	|3	|1	|6998.051197	|4.004796655|
|6	|3	|4	|12937.87987	|4.196132921|
|7	|3	|12	|8756.519521	|4.011758612|
|8	|4	|3	|12999.86912	|4.199918949|
|9	|4	|5	|16434.39247	|2.218844618|
|10	|4	|11	|5391.820399	|7.310006251|
|11	|5	|4	|16555.1137	|2.225346037|
|12	|5	|6	|8458.701638	|9.124469389|
|13	|5	|9	|14538.12276	|8.350384034|
|14	|6	|2	|5715.184898	|6.324015053|
|15	|6	|5	|8483.750272	|9.185439621|
|16	|6	|8	|11735.13663	|11.88075941|
|17	|7	|8	|10638.79404	|4.524461869|
|18	|7	|18	|14733.4668	|2.099800771|
|19	|8	|6	|11736.12307	|11.88408207|
|20	|8	|7	|10747.89645	|4.587964746|
|21	|8	|9	|5760.221791	|12.53872773|
|22	|8	|16	|7827.593875	|8.73326592|
|23	|9	|5	|14633.79536	|8.439451367|
|24	|9	|8	|5726.378296	|12.47958753|
|25	|9	|10	|21386.32473	|5.51030143|
|26	|10	|9	|21548.15383	|5.587149439|
|27	|10	|11	|16475.4057	|9.472067532|
|28	|10	|15	|22185.71471	|11.31180911|
|29	|10	|16	|12017.50016	|16.13351902|
|30	|10	|17	|7535.465401	|13.49834859|
|31	|11	|4	|5433.088429	|7.350575269|
|32	|11	|10	|16476.64108	|9.473073597|
|33	|11	|12	|8357.286284	|11.92166692|
|34	|11	|14	|10269.31703	|11.47115543|
|35	|12	|3	|8718.592461	|4.011556212|
|36	|12	|11	|8562.386639	|12.36843385|
|37	|12	|13	|13574.23054	|3.086374894|
|38	|13	|12	|13841.40384	|3.09157613|
|39	|13	|24	|13076.92821	|10.59722936|
|40	|14	|11	|10206.72008	|11.33536453|
|41	|14	|15	|8542.05203	|9.623416231|
|42	|14	|23	|7747.349587	|6.474746777|
|43	|15	|10	|22174.39696	|11.303684|
|44	|15	|14	|8442.256618	|9.463258119|
|45	|15	|19	|20739.90418	|4.520787372|
|46	|15	|22	|20551.88685	|6.437924555|
|47	|16	|8	|7971.526224	|8.943015724|
|48	|16	|10	|12040.81333	|16.20427083|
|49	|16	|17	|11700.2239	|4.502475927|
|50	|16	|18	|13068.60855	|3.330730565|
|51	|17	|10	|7584.063702	|13.60541726|
|52	|17	|16	|11746.8099	|4.522443483|
|53	|17	|19	|11936.87864	|5.061581438|
|54	|18	|7	|14624.36438	|2.097600052|
|55	|18	|16	|13189.26807	|3.33686588|
|56	|18	|20	|17006.53316	|4.528045022|
|57	|19	|15	|20661.72733	|4.50934409|
|58	|19	|17	|12032.06294	|5.110602018|
|59	|19	|20	|9254.187016	|7.4220289|
|60	|20	|18	|16918.09026	|4.522567081|
|61	|20	|19	|9271.194473	|7.43461855|
|62	|20	|21	|6241.379074	|8.282266702|
|63	|20	|22	|7082.26767	|7.433678897|
|64	|21	|20	|6085.158251	|8.169446912|
|65	|21	|22	|10153.77612	|3.88467613|
|66	|21	|24	|12616.08859	|8.001704292|
|67	|22	|15	|20418.95053	|6.393593156|
|68	|22	|20	|7067.053053	|7.423233735|
|69	|22	|21	|10865.32456	|4.158077171|
|70	|22	|23	|11214.48373	|9.030585813|
|71	|23	|14	|7784.548052	|6.498568545|
|72	|23	|22	|11777.88123	|9.548739453|
|73	|23	|24	|7715.470367	|3.154044254|
|74	|24	|13	|13244.1015	|10.76698331|
|75	|24	|21	|11748.31933	|7.337305741|
|76	|24	|23	|8316.066335	|3.340705953|


### Z(x)
![Z(x)](/result/z.jpg)
### Convergence Score
![Convergence Score](/result/convergence_score.jpg)