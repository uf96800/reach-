3.it is published.

4.while invariant after loop
  at ./index.rsh:54:7:invariant

  // Violation witness
  const interact_Alice_wager = 0;
  //    ^ from interaction at ./index.rsh:34:12:application
  const balance/204 = 0;
  //    ^ from loop variable at ./index.rsh:55:7:while

  // Theorem formalization
  invariant((balance/204 == (2 * interact_Alice_wager)) ? ((0 <= 10) ? (10 < 3) : #f) : #f);

5.(1)对 （2）对 （3）错

备注：nhujj（赏金网站id）
