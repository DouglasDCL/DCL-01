ul ,  li ,  nav ,  um {
  margem :  0 ;
  preenchimento :  0 ;
}
um {
  decoração de texto : nenhuma;
  família de fontes : hevetica;
}
# menu vertical {
  margem superior :  20 px ;
  exibição : bloco em linha;
  raio da borda :  5 
  box-sizing : border-box;
  padding-left :  10 px ;
  fundo :  # bd12ba ;
  margem esquerda :  80 px ;
}
# menu-principal {
  exibição : bloco em linha;
  largura :  100 % ;
  box-sizing : border-box;
}
. menu-principal  li {
  posição : relativa;
  estilo de lista : nenhum;
  altura :  50px ; _
  box-shadow :  0  -1 px  0  0  # 444 ,  0  -2 px  0  0  # 222 ;
}
. menu-principal > li > a > i {
  cor :  # bd12ba ;
  largura :  2 em ;
  altura :  100 % ;
  altura da linha :  50 px ;
  text-align : esquerda;
}
. menu-principal > li : first-child ,
. submenu-1 > li : primeiro filho {
  box-shadow : nenhum;
}
. menu-principal > li : first-child > a ,
. submenu-1 > li : primeiro filho > a {
  borda-topo-esquerda-raio :  5 px ;
  border-top-right-radius :  5 px ;
}
. menu-principal > li : último filho > a ,
. submenu-1 > li : último filho > a {
  border-bottom-left-radius :  5 px ;
  border-bottom-right-radius :  5 px ;
}
. menu-principal > li > a ,
. submenu-1 > li > a {
  cor :  # bd12ba ;
  fundo :  # 2a2a2a ;
  altura da linha :  50 px ;
  exibição : bloco;
  preenchimento :  0  1 em ;
}
. submenu-1 {
  posição : absoluta;
  espaço em branco : nowrap;
  topo :  -9999px ; _
}
. contém-submenu > a : first-child :: after {
  conteúdo :  "\f054" ;
  padding-left :  1 em ;
  font-family :  'FontAwesome' ;
}
. menu-principal > li : hover
. submenu-1 ,
. submenu-1 . li : pairar {
  topo :  0 ;
  esquerda :  100 % ;
  transição : top 0,5 s  cúbico-bezier ( 0,380 ,  0,820 ,  0,790 , 0,930 );
}
. menu-principal > li : hover > a {
  cor :  # e87a13 ;
}
. submenu-1  li : hover > a {
  cor :  # 0b8922
}
