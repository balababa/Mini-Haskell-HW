NCCUCS PL Assignment 5
Due date:  13:00,  May 1, 2018  (Assignment-5.hs)
作業寫作前可以與同學討論，但要下筆時，請自己寫，不要抄襲。
     注意： 函式名稱必須照題目中的命名。

1.	目前給定的Mini-Haskell interpreter尚未實現部分expressions and Program的實作，,所以當輸入這類expressions或program時，會得到錯誤訊息如下:

	Eval.hs:ev1 env (Lam xs e) = Error "Lambda not implemented, your assignment 5"
	Eval.hs:ev1 env (Tuple es) = Error "Tuples not implemented, your assignment 5"
	Eval.hs:appOp Head (VList (v:vs)) = Error "Lists not implemented, your assignment 5"
	Eval.hs:appOp Tail (VList (v:vs)) = Error "Lists not implemented, your assignment 5"
	Eval.hs:appBinOp Cons  v      (VList vs) = Error " Lists implemented, your assignment 5"
	Eval.hs:appBinOp Cons  v      VNil    = Error "Lists not implemented, your assignment 5"
	Eval.hs:evalProg (Program decls e) =  Error "evalProg not implemented, your assignment 5. Define evalDecls in where to help."

本次作業請試著去不足這些未實現部分。

(a)	Tuple 20%
(b)	List 相關部分（cons, nil, head tail）40%
(c)	Lambda 20%
(d)	Program 20%
