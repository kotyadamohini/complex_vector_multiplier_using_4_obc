# complex_vector_multiplier_using_4_obc
As we know two complex numbers multiplication takes 4 multipliers.And we can optimize it by using DA and OBC techniques.Now it can also be done incase of vectors. So,here we took two complex vectors and we found their product in both cases of DA and OBC.we know that Yre = XreAre-XimAim Imaginary part: Yim = XreAim+XimAre.
we already observed that,in OBC LUT size is half compare to DA and accessing time is also less.So,for the four multiplications,we instatiated four OBC bloks parallelly.
In this case we get output after K clock cycles.Throughput is high.
