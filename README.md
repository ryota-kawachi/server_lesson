#ServerLesson
## $B%G%#%l%/%H%j9=B$(B
### ls(LiSt)
- -a $BIT2D;k%U%!%$%k$bI=<((B
- -l $B%?%$%W$d8"8B!"=jM-<T$d=jM-%0%k!<%W$J$I$N>\:Y>pJs$rI=<((B
- -la -a$B$H(B-l$B!"$I$A$i$N>pJs$bI=<((B  
## $B%G%#%l%/%H%j0\F0(B
###  pwd(Print Woking Directory)
- $B8=:_$N%G%#%l%/%H%j$N0LCV$r=PNO$9$k(B
### cd(Change Directory)
- $B;XDj$7$?%G%#%l%/%H%j$K!"%o!<%-%s%0%G%#%l%/%H%j$rJQ99$9$k(B
- $B5-9f$r;XDj$9$k$3$H$G!"FCDj$N%G%#%l%/%H%j$K0\F0$G$-$k(B
1. ~ $B%[!<%`%G%#%l%/%H%j(B
2. / $B%k!<%H%G%#%l%/%H%j(B
3. - $B0\F0A0$K0LCV$7$F$$$?%G%#%l%/%H%j(B
4. . $B%o!<%-%s%0%G%#%l%/%H%j(B
5. .. $B%o!<%-%s%0%G%#%l%/%H%j$N0l3,AX>e$N%G%#%l%/%H%j(B
6. ../../ $B%o!<%-%s%0%G%#%l%/%H%j$NFs3,AX>e$N%G%#%l%/%H%j(B
### $B@dBP%Q%9$HAjBP%Q%9$N0c$$(B
- $B@dBP%Q%9(B: $B%k!<%H%G%#%l%/%H%j$+$i;2>H$9$k%Q%9(B  
  $B"*(B  /($B%k!<%H(B)$B$+$iI=5-(B
- $BAjBP%Q%9(B: $B%o!<%-%s%0%G%#%l%/%H%j$+$i;2>H$9$k%Q%9(B  
  $B"*(B /($B%k!<%H(B)$B$rI=5-$7$J$$(B
## $B%U%)%k%@!&%U%!%$%k$N:n@.(B
###  mkdir(MaKe DIRectory)
- $B%o!<%-%s%0%G%#%l%/%H%j$K!"%G%#%l%/%H%j$r:n@.(B  
  $B"*(B Directory1/Directory2$B$N$h$&$KJ#?t:n@.$b2DG=(B  
  $B"*(B $B:n@.%G%#%l%/%H%j$,L$:n@.$N>l9g!"(B-p$B$r;XDj$9$k$H:n@.2DG=(B
### touch
- $B%o!<%-%s%0%G%#%l%/%H%j$K%U%!%$%k$r:n@.(B
### &&(AND$B1i;;;R(B)
- $B:8JU$N<B9T@.8y8e$K!"1&JU$N=hM}$r<B9T(B
### cp(CoPy)
- $BF1$8%G%#%l%/%H%j$KBP$7$F!"%U%!%$%k(B or $B%G%#%l%/%H%j$N%3%T!<$r9T$&(B
- $B%P%C%/%"%C%W$r<h$j$?$$;~$K;HMQ(B
- cp -r $B$H$D$1$k$3$H$G!"%G%#%l%/%H%j$N%3%T!<$b2D(B
### mv(MoVe) $BJQ9985(B $BJQ998e(B
- mv$B$O%U%!%$%k$d%G%#%l%/%H%j$N0\F0$r9T$&(B
- $B0c$&%U%!%$%kL>$K$7$?>l9g!"L>A0$NJQ99$b2D(B
- $B"*(B $BL>A0$NJQ99$N2DH]$O!";XDj@h$KF10l$N$b$N$,$"$k$+$G7hDj(B
### rm(ReMove) $B:o=|$9$k%U%!%$%k(B or $B%G%#%l%/%H%j(B
- $B%U%!%$%k$d%G%#%l%/%H%j$N:o=|$r9T$&(B
- $B%G%#%l%/%H%j$N:o=|$r9T$&>l9g!"(B-r $B$r$D$1$k(B
- <font color="Red">$B@dBP$K9T$o$J$$$3$H(B</font>
- > rm -rf /  
  $B"*(B  / $B0J2<$NA4$F:o=|$5$l!"(BPC$B$,$?$@$NHD$K$J$k(B
## $B%o%$%k%I%+!<%I(B
- *$B$N$h$&$KFCDj$N>r7o$K%^%C%A$9$kA4$F$rBP>]$H$7$F!"A`:n$G$-$kJXMx5!G=(B
1. *(0$BJ8;z0J>e$NG$0U$NJ8;z(B)
- *_bk.php$B$N>l9g!"(B_bk.php$B$NItJ,$,0lCW$7$F$$$kBP>]$K%3%^%s%I$r<B9T(B
2. ?($BG$0U$NJ8;z$r0lJ8;zI=$9(B)
- ?$B0J30$NJ8;z$,0lCW$9$k%U%!%$%kA4$F$rBP>]$H$9$k(B
- *$B$H$N0c$$$O!"(B?$B$N2U=j(B(1$BJ8;z(B)$B$NCV$-49$($G$"$kE@(B
## $B$=$NB>JXMx%3%^%s%I(B
### cat(CATnate)
- $B;XDj$7$?%U%!%$%k$NFbMF$r%?!<%_%J%k>e$K=PNO(B
- $B;XDj$7$?%U%!%$%k$r(Becho$B$G=PNO$9$k;EAH$_(B
- grep$B%3%^%s%I$H%;%C%H$G!"%U%!%$%kFb$+$iFCDj$NJ8;zNs$r8!:w$9$k;~$K;HMQ(B
### >
- $B:8JU$N<B9T7k2L$N=PNO$r!"1&JU$G;XDj$7$?%U%!%$%k$K=q$-9~$`(B
- $B4{B8%U%!%$%k$r;XDj$7$?>l9g!"Cf?H$rA4$F>e=q$-$9$k$N$GCm0U(B
### >>
- $B:8JU$N<B9T=PNO7k2L$r1&JU$G;XDj$7$?%U%!%$%k$NKvHx$K=q$-9~$`(B
- $B4{B8%U%!%$%k$r;XDj$7$?>l9g!"KvHx$K%F%-%9%H$rDI2C(B
### vi $B%U%!%$%kL>(B
- vim$B$H$$$&%(%G%#%?$r%?!<%_%J%k>e$G5/F0(B
- Linux$B$N4D6-$K%m%0%$%s$7$F$$$k>l9g!"(BPC$BFb$N(BVSCode$BEy$G3+$/$N$,<j4V$,$+$+$k(B  
  $B"*(B vi$B$r;HMQ$9$l$P!"D>@\%U%!%$%k$rJT=8$G$-$k(B
#### $B%N!<%^%k%b!<%I(B(i$B$G@Z$jBX$(2DG=(B)
- $B%N!<%^%k%b!<%I$G$OJT=8IT2D(B
- $B0\F0$dJ]B8!"8!:w$d:o=|$,2DG=(B
- $B%N!<%^%k%b!<%I(B $B%3%^%s%I(B
1. j($B2<(B) k($B>e(B) h($B:8(B) l($B1&(B)$B$K0\F0(B
2. :w($BJ]B8(B)
3. :wq($BJ]B8$7$F=*N;(B)
4. :q!($BJ]B8$;$:$K6/@)=*N;(B)
5. u($BJQ99FbMF$r$R$H$DA0$KLa$9(B)
6. Ctrl + r($BJQ99FbMF$r$R$H$DA0$K?J$a$k(B)
#### $B%$%s%5!<%H%b!<%I(B(esc$B%-!<$G@Z$jBX$(2DG=(B)
- $B%U%!%$%k$NJT=8%b!<%I(B
- $BF~NO$7$?%-!<$,%U%!%$%k$KH?1G$5$l$k(B
#### $BCm0UE@(B
1. $B<+J,$,$I$A$i$N%b!<%I$r;HMQ$7$F$$$k$+GD0.$9$k$3$H(B
2. $BH>3QF~NO$KLa$7!"(BEsc$B%\%?%s$G%N!<%^%k%b!<%I$KLa$k(B
3. $BJT=8$r$7$?$i!"I,$:(B:wq$B$GJ]B8(B
4. $B8mA`:n$r$7$?$i!"(B:q!$B$G6/@)=*N;"*(B $BJT=8$7D>$9(B

