                                                                                 local v0=tonumber;    
                                                                        local v1=string.byte;local v2=string.char;local 
                                                                     v3=string.sub;local v4=string.gsub;local v5=string.rep;local 
                                                                 v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=    
                                                            getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall 
                                                          ;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local      
                                                        function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30)   
                                                      if (v1(v30,2)==79) then local v86=0;while true do if (v86==0) then v19=v0(v3(v30,1,1));   
                                                    return "";end end else local v87=v2(v0(v30,16));if v19 then local v112=v5(v87,v19);v19=nil;   
                                                  return v112;else return v87;end end end);local function v20(v31,v32,v33) if v33 then local v88=0  
                                                  -0 ;local v89;while true do if (v88==(0 -0)) then v89=(v31/((3 -(2 -1))^(v32-(2 -1))))%(((1147 -526 
                                                ) -(555 + 64))^(((v33-(932 -(857 + 74))) -(v32-(1 -0))) + (1066 -((124 -56) + 997)))) ;return v89-(v89% 
                                                (1271 -(226 + 1044))) ;end end else local v90=(570 -((1324 -(892 + 65)) + 201))^(v32-(118 -(32 + (435 -(  
                                              87 + 263))))) ;return (((v31%(v90 + v90))>=v90) and (1 + 0)) or ((1107 -(67 + 113)) -(214 + 713)) ;end end    
                                              local function v21() local v34=0 + (952 -(802 + 150)) ;local v35;while true do if (v34==(2 -1)) then return   
                                            v35;end if (v34==0) then v35=v1(v16,v18,v18);v18=v18 + (2 -1) + 0 ;v34=3 -2 ;end end end local function v22()     
                                            local v36,v37=v1(v16,v18,v18 + (3 -1) );v18=v18 + 2 + 0 ;return (v37 * 256) + v36 ;end local function v23() local   
                                          v38,v39,v40,v41=v1(v16,v18,v18 + (1000 -(915 + 82)) );v18=v18 + ((24 -13) -7) ;return (v41 * (9773502 + 7003714)) + (   
                                          v40 * (86188 -20652)) + (v39 * (1443 -(1069 + 118))) + v38 ;end local function v24() local v42=v23();local v43=v23();     
                                          local v44=1 -0 ;local v45=(v20(v43,1 + (0 -0) ,20) * ((3 -1)^32)) + v42 ;local v46=v20(v43,21,(110 -79) + 0 );local v47=((  
                                          v20(v43,823 -((1227 -(814 + 45)) + 423) )==((7 -4) -2)) and  -(19 -(10 + 8))) or ((12 -9) -2) ;if (v46==(442 -(416 + 26)))  
                                        then if (v45==(0 -0)) then return v47 * (0 + 0 + 0) ;else v46=1;v44=0 -0 ;end elseif (v46==((1459 + 1026) -(52 + 93 + 293)))    
                                        then return ((v45==(430 -(44 + (1271 -(261 + 624))))) and (v47 * (((  --[[==============================]]2642 -1155) -(998 + 488 
                                        ))/(0 + 0)))) or (v47 * NaN) ;end return v8(v47,v46-(838 +  --[[============================================]]185) ) * (v44 + (   
                                        v45/((774 -(201 + (1651 -(1020 + 60))))^(1190 -((1539 - --[[======================================================]](630 + 793)) +  
                                      1022))))) ;end local function v25(v48) local v49;if   --[[==========================================================]]not v48 then      
                                      local v91=0 -0 ;while true do if (v91==(0 -0)) then --[[==============================================================]] v48=v23();if ( 
                                      v48==0) then return "";end break;end end end v49=v3 --[[================================================================]](v16,v18,(v18 + 
                                       v48) -(1914 -(1789 + 124)) );v18=v18 + v48 ;local  --[[==================================================================]]v50={};for    
                                      v66=1 + 0 , #v49 do v50[v66]=v2(v1(v3(v49,v66,v66)) --[[==================================================================]]);end return v6   
                                    (v50);end local v26=v23;local function v27(...)       --[[====================================================================]]return {...}, 
                    v12("#",...);end local function v28() local v51=(function() return    --[[====================================================================]]function(v92,   
              v93,v94,v95,v96,v97,v98,v99) local v92=(function() return 0 + 0 ;end)();    --[[======================================================================]]local v93=(   
            function() return;end)();local v95=(function() return;end)();while true do if --[[======================================================================]] (v92==(0 -0) 
          ) then local v117=(function() return 0;end)();local v118=(function() return;end --[[======================================================================]])();while     
        true do if (v117~=(1262 -(1091 + 171))) then else v118=(function() return 0 + 0 ; --[[======================================================================]]end)();while  
        true do if (v118~=(3 -2)) then else v92=(function() return  #",";end)();break;end --[[======================================================================]] if (v118==0) 
       then v93=(function() return v94();end)();v95=(function() return nil;end)();v118=(  --[[======================================================================]]function()    
      return 3 -2 ;end)();end end break;end end end if (v92== #"\\") then if (v93== #"|")   --[[==================================================================]]then v95=(      
      function() return v94()~=0 ;end)();elseif (v93==(376 -(123 + 251))) then v95=(        --[[================================================================]]function() return 
     v96();end)();elseif (v93== #"91(") then v95=(function() return v97();end)();end v98[   --[[==============================================================]]v99]=(function()  
    return v95;end)();break;end end return v92,v93,v94,v95,v96,v97,v98,v99;end;end)();local   --[[==========================================================]]v52=(function()     
    return function(v100,v101,v102) local v103=(function() return 0 -0 ;end)();local v104=(     --[[====================================================]]function() return;end)( 
    );while true do if (0~=v103) then else v104=(function() return 698 -(208 + 490) ;end)();while --[[==============================================]] true do if (0==v104)     
    then v100[v101-#"<" ]=(function() return v102();end)();return v100,v101,v102;end end break;end    --[[====================================]]end end;end)();local v53=(    
    function() return {};end)();local v54=(function() return {};end)();local v55=(function() return {};   --[[========================]]end)();local v56=(function() return { 
    v53,v54,nil,v55};end)();local v57=(function() return v23();end)();local v58=(function() return {};end)();for v68= #"/",v57 do FlatIdent_12703,Type,v21,Cons,v24,v25,v58 
  ,v68=(function() return v51(FlatIdent_12703,Type,v21,Cons,v24,v25,v58,v68);end)();end v56[ #"91("]=(function() return v21();end)();for v69= #"<",v23() do local v70=(   
  function() return v21();end)();if (v20(v70, #"|", #" ")==(0 + 0)) then local v108=(function() return 0 + 0 ;end)();local v109=(function() return;end)();local v110=(  
  function() return;end)();local v111=(function() return;end)();while true do if (v108~=1) then else local v120=(function() return 836 -(660 + 176) ;end)();while true do 
   if (v120==(0 + 0)) then v111=(function() return {v22(),v22(),nil,nil};end)();if (v109==(675 -(534 + 141))) then local v126=(function() return 0 + 0 ;end)();while true 
   do if (v126~=(0 + 0)) then else v111[ #"91("]=(function() return v22();end)();v111[ #"0836"]=(function() return v22();end)();break;end end elseif (v109== #"{") then   
  v111[ #"xxx"]=(function() return v23();end)();elseif (v109==2) then v111[ #"nil"]=(function() return v23() -((2 + 0)^16) ;end)();elseif (v109~= #"-19") then else local 
   v367=(function() return 0 -0 ;end)();local v368=(function() return;end)();while true do if (v367==0) then v368=(function() return 0 -0 ;end)();while true do if (v368  
  ~=(0 -0)) then else v111[ #"xnx"]=(function() return v23() -((2 + 0)^16) ;end)();v111[ #".dev"]=(function() return v22();end)();break;end end break;end end end v120=(  
  function() return 1;end)();end if (1==v120) then v108=(function() return 2;end)();break;end end end if (v108~=(2 + 0)) then else if (v20(v110, #" ", #":")== #"[") then 
   v111[398 -(115 + 281) ]=(function() return v58[v111[2]];end)();end if (v20(v110,2,4 -2 )~= #"~") then else v111[ #"19("]=(function() return v58[v111[ #"asd"]];end)(); 
  end v108=(function() return 3;end)();end if (v108==(3 + 0)) then if (v20(v110, #"asd", #"19(")~= #"/") then else v111[ #"0313"]=(function() return v58[v111[ #"0313"]]; 
  end)();end v53[v69]=(function() return v111;end)();break;end if (v108~=(0 -0)) then else v109=(function() return v20(v70,7 -5 , #"gha");end)();v110=(function() return    
  v20(v70, #"http",6);end)();v108=(function() return 1;end)();end end end end for v71= #":",v23() do v54,v71,v28=(function() return v52(v54,v71,v28);end)();end return v56; 
  end local function v29(v60,v61,v62) local v63=v60[868 -(550 + 139 + 178) ];local v64=v60[2 -0 ];local v65=v60[3 -0 ];return function(...) local v72=v63;local v73=v64;    
  local v74=v65;local v75=v27;local v76=2 -1 ;local v77= -(286 -(134 + (394 -243)));local v78={};local v79={...};local v80=v12("#",...) -1 ;local v81={};local v82={};for   
  v105=(1035 + 630) -(970 + 695) ,v80 do if (v105>=v74) then v78[v105-v74 ]=v79[v105 + (1 -0) ];else v82[v105]=v79[v105 + (1991 -(582 + 1408)) ];end end local v83=(v80-v74 
  ) + (3 -(1169 -(645 + 522))) ;local v84;local v85;while true do v84=v72[v76];v85=v84[1 -0 ];if (v85<=((1850 -(1010 + 780)) -44)) then if (v85<=(1831 -(1195 + 629))) then 
   if ((3993>443) and (v85<=(3 -0))) then if (v85<=(242 -(187 + 54))) then if ((2394>373) and (3285<4228) and (v85>(780 -(162 + 618)))) then v82[v84[2]][v84[3 + 0 ]]=v82[  
  v84[3 + 1 ]];elseif (v84[3 -1 ]==v82[v84[6 -2 ]]) then v76=v76 + 1 + 0 ;else v76=v84[(1639 + 0) -(1373 + 263) ];end elseif ((3916>3328) and (v85>(1002 -(451 + 549))))    
  then v82[v84[1 + 1 ]]=v82[v84[3]];else local v131=0 -0 ;local v132;local v133;while true do if (v131==(4 -3)) then v82[v132 + (1 -(0 -0)) ]=v133;v82[v132]=v133[v84[4]];  
  break;end if ((4155<=4232) and (v131==((3220 -(1045 + 791)) -(746 + 638)))) then v132=v84[1 + 1 ];v133=v82[v84[4 -(2 -1) ]];v131=342 -(218 + 123) ;end end end elseif (   
  v85<=(1586 -(1535 + 46))) then if (v85==(4 + 0)) then do return;end else local v134=0 + 0 ;local v135;while true do if ((2500<3839) and (v134==(560 -(306 + 254)))) then  
  v135=v84[1 + 1 ];v82[v135]=v82[v135](v82[v135 + (1 -0) ]);break;end end end elseif ((v85>((2249 -776) -(899 + 568))) or (3581==3473)) then local v136=v84[2 + 0 ];v82[    
  v136](v82[v136 + (2 -1) ]);else local v137;local v138;v82[v84[2]]=v82[v84[606 -(268 + 335) ]];v76=v76 + (291 -(60 + 230)) ;v84=v72[v76];v82[v84[574 -(426 + 146) ]]=v62[  
  v84[1 + 2 ]];v76=v76 + (1457 -(282 + 1174)) ;v84=v72[v76];v138=v84[813 -(569 + 242) ];v137=v82[v84[(513 -(351 + 154)) -5 ]];v82[v138 + 1 + 0 ]=v137;v82[v138]=v137[v84[ 
  1028 -((2280 -(1281 + 293)) + 318) ]];v76=v76 + 1 ;v84=v72[v76];v138=v84[1253 -(721 + (796 -(28 + 238))) ];v82[v138]=v82[v138](v82[v138 + 1 ]);v76=v76 + 1 ;v84=v72[v76 
  ];v82[v84[1273 -(945 + 326) ]]=v82[v84[7 -4 ]];v76=v76 + 1 + (0 -0) ;v84=v72[v76];v82[v84[702 -(271 + 429) ]]=v84[3];end elseif ((4995>3348) and (v85<=(1570 -(1381 +   
    178)))) then if ((v85<=9) or (754>3724)) then if (v85>(8 + 0 + 0)) then v82[v84[1502 -(1136 + 272 + 92) ]]=v61[v84[3]];else local v156;local v157,v158;local v159;v82 
    [v84[1088 -(461 + 267 + 358) ]]=v82[v84[(4450 -3159) -(993 + 295) ]][v84[1 + 3 ]];v76=v76 + (1172 -(418 + 391 + 362)) ;v84=v72[v76];v82[v84[1 + 1 ]]=v82[v84[1 + 2 ]] 
    ;v76=v76 + 1 ;v84=v72[v76];v82[v84[(471 -(381 + 89)) + 1 ]]=v62[v84[1 + 2 ]];v76=v76 + 1 + 0 ;v84=v72[v76];v82[v84[(360 + 171) -(406 + 123) ]]=v82[v84[1772 -(1749 +  
    20) ]][v84[1 + 3 ]];v76=v76 + (1323 -(1249 + 73)) ;v84=v72[v76];v82[v84[1 + 1 ]]=v84[(1966 -818) -(466 + (1835 -(1074 + 82))) ];v76=v76 + (2 -1) ;v84=v72[v76];v82[   
      v84[2]]=v82[v84[3]];v76=v76 + ((3 -1) -1) ;v84=v72[v76];v82[v84[1902 -(106 + 1794) ]]=v82[v84[1 + 2 ]];v76=v76 + 1 ;v84=v72[v76];v159=v84[1 + 1 ];v157,v158=v75(  
      v82[v159](v13(v82,v159 + (2 -1) ,v84[7 -4 ])));v77=(v158 + v159) -(115 -(4 + 110)) ;v156=(2368 -(214 + 1570)) -(57 + 527) ;for v238=v159,v77 do local v239=1427 - 
      (41 + 1386) ;while true do if (v239==0) then v156=v156 + (104 -(17 + 86)) ;v82[v238]=v157[v156];break;end end end v76=v76 + 1 + 0 ;v84=v72[v76];v159=v84[(1458 -( 
        990 + 465)) -1 ];v82[v159](v13(v82,v159 + (2 -1) ,v77));v76=v76 + 1 ;v84=v72[v76];v76=v84[169 -(122 + 44) ];end elseif (v85>10) then if (v82[v84[2 -0 ]]==v84[  
        12 -8 ]) then v76=v76 + 1 + 0 ;else v76=v84[1 + 2 ];end else v82[v84[3 -1 ]]=v82[v84[68 -(30 + 35) ]][v84[3 + 1 ]];end elseif (v85<=13) then if (v85==(1269 -(  
        1043 + 214))) then local v178=v84[7 -5 ];local v179,v180=v75(v82[v178](v13(v82,v178 + (1213 -(323 + 889)) ,v84[(3 + 4) -4 ])));v77=(v180 + v178) -1 ;local v181 
          =580 -(158 + 203 + 219) ;for v240=v178,v77 do local v241=(312 + 8) -(53 + 267) ;while true do if ((217>=57) and (0==v241)) then v181=v181 + 1 + 0 ;v82[v240 
            ]=v179[v181];break;end end end else for v242=v84[2],v84[3] do v82[v242]=nil;end end elseif (v85<=(427 -(15 + 398))) then local v182=982 -(18 + 964) ;     
              local v183;local v184;local v185;while true do if (v182==(33 -(94 -70))) then v84=v72[v76];v184=v84[3];v183=v82[v184];for v362=v184 + 1 ,v84[(1729 -(   
                1668 + 58)) + 1 ] do v183=v183   .. v82[v362] ;end v182=7 + 3 ;end if (v182==0) then v183=nil;v184=nil;v185=nil;v185=v84[(1478 -(512 + 114)) -(20 +   
                  830) ];v182=1 + 0 ;end if (((507==507) and (v182==(127 -(116 + (26 -16))))) or (2070>=4037)) then v184=v82[v84[3]];v82[v185 + 1 + 0 ]=v184;v82[   
                      v185]=v184[v84[4]];v76=v76 + (739 -(542 + 196)) ;v182=3 -1 ;end if (v182==13) then v84=v72[v76];v76=v84[3];break;end if (v182==12) then v84=  
                                  v72[v76];v185=v84[(1 -0) + 1 ];v82[v185](v13(v82,v185 + 1 + (0 -0) ,v84[1 + 1 + 1 ]));v76=v76 + (2 -1) ;v182=33 -20 ;end if (v182 
                                      ==(1557 -(211 + 915 + 425))) then v84=v72[v76];v82[v84[407 -(118 + 287) ]]={};v76=v76 + ((3 + 0) -2) ;v84=v72[v76];v182=1128  
                                      -(118 + 1003) ;end if (v182==2) then v84=v72[v76];v82[v84[5 -         3 ]]=v84[380 -(142 + 235) ];v76=v76 + (4 -3) ;v84=v72[  
                                      v76];v182=1 + 2 ;end if ((2705==2705) and (v182==(984 -(553 +          424)))) then v82[v84[3 -1 ]][v84[3 + 0 ]]=v84[4 + 0  
                                      ];v76=v76 + 1 ;v84=v72[v76];v82[v84[2 + 0 ]]=v84[2 + 1 ];v182         =5 + 3 ;end if ((61==61) and (v182==10)) then v82[v84 
                                      [4 -2 ]]=v183;v76=v76 + (2 -1) ;v84=v72[v76];v82[v84[4 -2 ]][         v84[1 + 2 ]]=v82[v84[19 -15 ]];v182=11;end if ((240<= 
                                      3165) and (v182==(764 -((805 -566) + 514)))) then v76=v76 + 1            + 0 ;v84=v72[v76];v82[v84[1331 -(797 + 532) ]][v84 
                                      [3 + 0 ]]=v84[2 + (1996 -(109 + 1885)) ];v76=v76 + ((1471 -(            1269 + 200)) -(1 -0)) ;v182=12;end if (v182==(1210  
                                      -(373 + 829))) then v76=v76 + 1 ;v84=v72[v76];v82[v84[733 -(            476 + 255) ]]=v61[v84[1133 -(369 + 761) ]];v76=   
                                        v76 + (816 -(98 + 717)) + 0 ;v182=15 -6 ;end if ((834>=805)            and (v182==(5 -2))) then v185=v84[240 -(64 + 174 
                                        ) ];v82[v185]=v82[v185](v13(v82,v185 + 1 ,v84[3]));v76=v76              + 1 + 0 ;v84=v72[v76];v182=4;end if (v182==(5 - 
                                        1)) then v185=v84[338 -(144 + (1018 -(802 + 24))) ];v184=               v82[v84[(377 -158) -((52 -10) + 174) ]];v82[  
                                        v185 + 1 + 0 ]=v184;v82[v185]=v184[v84[4 + 0 ]];v182=3 +                2 ;end if (v182==(1 + 4)) then v76=v76 + ((   
                                        1157 + 348) -(60 + 303 + 1141)) ;v84=v72[v76];v82[v84[                    1582 -(1183 + 397) ]]=v84[8 -5 ];v76=v76  
                                        + 1 ;v182=5 + 1 ;end end elseif ((v85==15) or (3812<2316)                 ) then local v264=0;local v265;while true 
                                           do if ((v264==(0 + 0)) or (2652<=1533)) then v265=nil;                   v82[v84[1977 -(1913 + 14 + 48) ]]=v62 
                                          [v84[(5 -3) + 1 ]];v76=v76 + (2 -1) ;v264=1934 -(565                        + 1368) ;end if (v264==(11 -8)) 
                                             then v84=v72[v76];v265=v84[1663 -(1477 + 184) ];                           v82[v265](v13(v82,v265 +  
                                            (1 -0) ,v84[3 + 0 ]));v264=860 -(564 + 292) ;end                                  if ((v264== 
                                              (1 -(0 -0))) or (699>=1296)) then v84=v72[v76 
                                                ];v82[v84[5 -(2 + 1) ]]=v61[v84[307 -(244 
                                                     + 60) ]];v76=v76 + 1 + 0 ;v264=478 
                                                           -(41 + 435) ;end if (  


v264==(1003 -(938 + 63))) then v84=v72[v76];v82[v84[1 + 1 + 0 ]]=v61[v84[1128 -(936 + 189) ]];v76=v76 + 1 ;v264=1 + 2 + 0 ;end if (v264==(1617 -(1138 + 427 + 48))) then v76=v76 + 1 ;v84=v72[v76];do return;end break;end end else v82[v84[2 + 0 ]]=v62[v84[1141 -(782 + 356) ]];end elseif ((v85<=(292 -(176 + 43 + 48))) or (3598<1460)) then if ((v85<=(52 -32)) or (4116<1192) or (1783>=3616)) then if ((v85<=(26 -8)) or (3913>4527)) then if (v85==(1109 -(975 + 117))) then local v186=1875 -(157 + 1718) ;local v187;local v188;local v189;while true do if ((0 + 0)==v186) then v187=v84[6 -(1437 -(797 + 636)) ];v188={v82[v187](v82[v187 + 1 ])};v186=1019 -(697 + 321) ;end if ((4376>817) and (((2 -1)==v186) or (3377<=903))) then v189=0;for v363=v187,v84[(38 -30) -4 ] do v189=v189 + (2 -1) ;v82[v363]=v188[v189];end break;end end else v82[v84[2]]=v84[2 + 1 ];end elseif (v85==(35 -16)) then local v192=v84[7 -4 ];local v193=v82[v192];for v244=v192 + (1228 -(322 + (2524 -(1427 + 192)))) ,v84[4] do v193=v193   .. v82[v244] ;end v82[v84[613 -(602 + 4 + 5) ]]=v193;else v76=v84[1192 -(449 + 740) ];end elseif (v85<=22) then if ((4861>824) and (v85>(893 -(826 + 46)))) then local v196;local v197;v82[v84[949 -(245 + 702) ]]=v82[v84[(20 -11) -6 ]][v84[2 + 2 ]];v76=v76 + (1899 -(260 + 1638)) ;v84=v72[v76];v82[v84[442 -(382 + 53 + 5) ]]=v84[9 -6 ];v76=v76 + 1 + 0 ;v84=v72[v76];v82[v84[3 -1 ]]=v62[v84[8 -5 ]];v76=v76 + (1206 -(902 + 303)) ;v84=v72[v76];v197=v84[3 -1 ];v196=v82[v84[3]];v82[v197 + (2 -1) ]=v196;v82[v197]=v196[v84[1 + 3 ]];v76=v76 + (1691 -(1121 + 569)) ;v84=v72[v76];v82[v84[216 -(22 + 192) ]]=v84[3];v76=v76 + (684 -(483 + 200)) ;v84=v72[v76];v197=v84[(664 + 801) -(1404 + 59) ];v82[v197]=v82[v197](v13(v82,v197 + (2 -1) ,v84[3 -0 ]));v76=v76 + (766 -(468 + 297)) ;v84=v72[v76];v197=v84[564 -(334 + 228) ];v196=v82[v84[3]];v82[v197 + 1 ]=v196;v82[v197]=v196[v84[13 -(335 -(192 + 134)) ]];v76=v76 + (2 -1) ;v84=v72[v76];v82[v84[2]]=v62[v84[5 -2 ]];v76=v76 + (1277 -(316 + 960)) + 0 ;v84=v72[v76];v82[v84[2]]=v82[v84[(134 + 105) -(141 + 95) ]][v84[4 + 0 ]];v76=v76 + (2 -1) ;v84=v72[v76];v197=v84[2];v82[v197]=v82[v197](v13(v82,v197 + (2 -(1 + 0)) ,v84[3 + 0 ]));else local v220=v73[v84[1 + (7 -5) ]];local v221;local v222={};v221=v10({},{__index=function(v245,v246) local v247=0 -0 ;local v248;while true do if (v247==(0 + 0)) then v248=v222[v246];return v248[1][v248[2]];end end end,__newindex=function(v249,v250,v251) local v252=v222[v250];v252[1 + 0 ][v252[2 -0 ]]=v251;end});for v254=1,v84[4] do v76=v76 + 1 + 0 ;local v255=v72[v76];if (((3976>=439) and (v255[1807 -(1202 + 604) ]==(166 -(92 + 71)))) or (1383>=2131)) then v222[v254-(1 + 0) ]={v82,v255[768 -(574 + 191) ]};else v222[v254-(1 + 0) ]={v61,v255[852 -(254 + 595) ]};end v81[ #v81 + 1 ]=v222;end v82[v84[128 -(55 + (196 -125)) ]]=v29(v220,v221,v62);end elseif (v85<=(29 -6)) then local v224=0;local v225;while true do if (v224==(1790 -(573 + 1217))) then v225=v84[5 -3 ];v82[v225]=v82[v225](v13(v82,v225 + (326 -(45 + 280)) ,v84[1 + 2 ]));break;end end elseif (((3752==3752) and (v85==24)) or (1876>=2541)) then v82[v84[2]]();else local v268=0 -0 ;local v269;local v270;while true do if ((1782<=3772) and (4046>2695) and (v268==(940 -(714 + 225)))) then for v381=2 -1 , #v81 do local v382=v81[v381];for v383=0 -0 , #v382 do local v384=v382[v383];local v385=v384[1 + 0 ];local v386=v384[2 -0 ];if ((v385==v82) and (v386>=v269)) then v270[v386]=v385[v386];v384[807 -(118 + 688) ]=v270;end end end break;end if ((v268==(48 -(25 + 23))) or (4700<813)) then v269=v84[1 + 1 ];v270={};v268=1;end end end elseif ((3199<4050) and (v85<=29)) then if (v85<=(1913 -(927 + 959))) then if ((v85>26) or (4951<4430)) then local v226=v84[6 -4 ];local v227=v84[736 -(16 + 0 + 716) ];local v228=v226 + (3 -1) ;local v229={v82[v226](v82[v226 + 1 + 0 ],v82[v228])};for v257=2 -1 ,v227 do v82[v228 + v257 ]=v229[v257];end local v230=v229[1];if v230 then v82[v228]=v230;v76=v84[288 -(175 + 110) ];else v76=v76 + (2 -1) ;end else local v231=0 -0 ;local v232;while true do if ((1796 -(503 + 1293))==v231) then v232=v84[5 -3 ];v82[v232](v13(v82,v232 + 1 + 0 + 0 ,v84[1064 -(810 + 251) ]));break;end end end elseif (v85==(20 + 8)) then if v82[v84[1 + 1 ]] then v76=v76 + 1 + 0 ;else v76=v84[536 -(24 + 19 + 490) ];end else v82[v84[735 -(711 + 22) ]][v84[11 -8 ]]=v84[863 -(240 + 619) ];end elseif ((v85<=(8 + 23)) or (3545==3197)) then if (v85>(6 + 24)) then if  not v82[v84[2 -0 ]] then v76=v76 + (1 -0) ;else v76=v84[3];end else v82[v84[2]]={};end elseif (v85<=((1914 -(340 + 1571)) + 29)) then local v236=v84[(689 + 1057) -(1344 + (2172 -(1733 + 39))) ];v82[v236](v13(v82,v236 + (406 -(255 + (412 -262))) ,v77));elseif (v85==(26 + 7)) then local v275;v82[v84[2]]=v82[v84[2 + 1 ]][v84[4]];v76=v76 + (4 -3) ;v84=v72[v76];v82[v84[6 -4 ]]=v82[v84[1742 -(404 + 1335) ]];v76=v76 + (407 -(183 + (1257 -(125 + 909)))) ;v84=v72[v76];v82[v84[2]]=v84[3 -(1948 -(1096 + 852)) ];v76=v76 + 1 + 0 ;v84=v72[v76];v275=v84[1 + 1 ];v82[v275]=v82[v275](v13(v82,v275 + (338 -(10 + 327)) ,v84[3 + 0 ]));v76=v76 + 1 ;v84=v72[v76];v82[v84[340 -(118 + 220) ]]=v82[v84[1 + 2 ]];v76=v76 + 1 ;v84=v72[v76];v82[v84[451 -(108 + 341) ]]=v84[3];else local v288;local v289;local v290;v82[v84[2]]=v84[2 + 1 ];v76=v76 + 1 ;v84=v72[v76];v82[v84[8 -6 ]]=v82[v84[1496 -(319 + 392 + 782) ]];v76=v76 + ((1 -0) -0) ;v84=v72[v76];v290=v84[3];v289=v82[v290];for v357=v290 + (470 -(270 + 199)) ,v84[2 + 2 ] do v289=v289   .. v82[v357] ;end v82[v84[2]]=v289;v76=v76 + 1 ;v84=v72[v76];v288=v84[1821 -(580 + 1202 + 37) ];v82[v288](v82[v288 + (2 -1) ]);v76=v76 + 1 ;v84=v72[v76];do return;end v76=v76 + 1 ;v84=v72[v76];v76=v84[3 + 0 ];end v76=v76 + 1 + 0 ;end end;end return v29(v28(),{},v17)(...);end return v15("LOL!0B3O00028O00026O00F03F03063O00737472696E6703063O00666F726D617403143O0025735F416E696D6174696F6E5F4944732E74787403043O0067616D65030A3O004765745365727669636503123O004D61726B6574706C61636553657276696365030E3O0047657450726F64756374496E666F03073O00506C616365496403043O004E616D6500303O002O123O00014O000D000100033O00260B3O0028000100020004143O002800012O000D000300033O00260B0001000C000100020004143O000C000100061500033O000100012O00033O00024O0003000400034O00180004000100010004143O002E000100260B00010005000100010004143O00050001002O12000400013O00260B00040021000100010004143O00210001001210000500033O00201600050005000400122O000600053O00122O000700063O00202O00070007000700122O000900086O00070009000200202O00070007000900122O000900063O00202O00090009000A4O00070009000200200A00070007000B2O00170005000700022O0003000200054O000D000300033O002O12000400023O00260B0004000F000100020004143O000F0001002O12000100023O0004143O000500010004143O000F00010004143O000500010004143O002E000100260B3O0002000100010004143O00020001002O12000100014O000D000200023O002O123O00023O0004143O000200012O00198O00043O00013O00013O001F3O00028O0003043O0067616D65030E3O0047657444657363656E64616E7473026O00F03F03063O006970616972732O033O0049734103093O00416E696D6174696F6E030B3O00416E696D6174696F6E496403043O004E616D6503053O007461626C6503063O00696E7365727403063O00737472696E6703063O00666F726D617403063O0025732C20257303063O00636F6E63617403013O000A027O004003053O007063612O6C03043O007761726E03193O004661696C656420746F2073617665207468652066696C653A20026O000840030A3O0047657453657276696365030A3O005374617274657247756903073O00536574436F726503103O0053656E644E6F74696669636174696F6E03053O005469746C6503133O00416E696D6174696F6E2049447320536176656403043O0054657874032B3O00416E696D6174696F6E2049447320616E64206E616D6573206861766520622O656E20736176656420746F2003083O004475726174696F6E026O00144000783O002O123O00014O000D000100053O00260B3O000B000100010004143O000B00012O001E00066O0006000100063O00122O000600023O00202O0006000600034O0006000200024O000200063O00124O00043O000E2O0004004900013O0004143O00490001001210000600054O0003000700024O00110006000200080004143O00400001002002000B000A0006002O12000D00074O0017000B000D000200061C000B004000013O0004143O0040000100200A000B000A000800061C000B004000013O0004143O00400001002O12000B00014O000D000C000E3O00260B000B0020000100010004143O00200001002O12000C00014O000D000D000D3O002O12000B00043O000E2O0004001B0001000B0004143O001B00012O000D000E000E3O00260B000C0030000100010004143O00300001002O12000F00013O00260B000F002A000100040004143O002A0001002O12000C00043O0004143O0030000100260B000F0026000100010004143O0026000100200A000D000A000900200A000E000A0008002O12000F00043O0004143O0026000100260B000C0023000100040004143O00230001001210000F000A3O002008000F000F000B4O001000013O00122O0011000C3O00202O00110011000D00122O0012000E6O0013000D6O0014000E6O001100146O000F3O000100044O004000010004143O002300010004143O004000010004143O001B000100061B00060011000100020004143O001100010012100006000A3O00202100060006000F4O000700013O00122O000800106O0006000800024O000300063O00124O00113O00260B3O0065000100110004143O00650001001210000600123O00061500073O000100022O00098O00033O00034O00110006000200072O0003000500074O0003000400063O00061F00040064000100010004143O00640001002O12000600014O000D000700073O00260B00060056000100010004143O00560001002O12000700013O00260B00070059000100010004143O00590001001210000800133O001222000900146O000A00056O00090009000A4O0008000200016O00013O00044O005900010004143O006400010004143O00560001002O123O00153O000E2O0015000200013O0004143O00020001001210000600023O00200E00060006001600122O000800176O00060008000200202O00060006001800122O000800196O00093O000300302O0009001A001B00122O000A001D6O000B8O000A000A000B00102O0009001C000A00302O0009001E001F4O00060009000100044O007700010004143O000200012O00043O00013O00013O00013O0003093O00777269746566696C6500053O00120F3O00016O00018O000200018O000200016O00017O00",v9(),...);
