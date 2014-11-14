ECLille-poo
===========

jsfiddle test de modifications

Thomas B. : http://jsfiddle.net/tomnab/m3Ls0zeL/

http://jsfiddle.net/gwenaelhagenmuller/pk63z0x1/

http://www.typescriptlang.org/Playground#src=class%20Personne%20{%0A%20%20%20%20prenom%3A%20string%3B%0A%09nom%3A%20string%3B%20%0A%09oo%20%3A%20boolean%3B%0A%20%20%20%20public%20constructor%28prenom%3A%20string%2C%20nom%3A%20string%2C%20oo%20%3A%20boolean%29%20{%0A%20%20%20%20%20%20%20%20this.prenom%20%3D%20prenom%3B%0A%09%09this.nom%20%3D%20nom%3B%20%09%0A%09%09if%20%28oo%20!%3D%20null%29%20this.oo%20%3D%20oo%3B%0A%09%09else%20this.oo%20%3D%20false%3B%0A%20%20%20%20}%0A%09%0A%09setOO%28oo%20%3A%20boolean%29%20{%0A%09%09this.oo%20%3D%20oo%3B%20%0A%09}%20%20%20%0A%09%0A%09show%28%29%0A%09{%0A%09%09alert%28this.prenom%20%2B%20%22%20%22%20%2B%20this.nom%20%0A%09%09%09%2B%28%28this.oo%29%3F%20%22%20connait%22%20%3A%20%22%20ne%20connait%20pas%22%29%29%3B%09%0A%09}%0A%09%0A%09getPinT%28%29%0A%09{%0A%09%09return%20%09%22%3Ctr%3E%3Ctd%3E%22%20%2B%20this.prenom%20%2B%20%22%3C%2Ftd%3E%3Ctd%3E%22%20%2B%20this.nom%0A%09%09%09%2B%20%22%3C%2Ftd%3E%3C%2Ftd%3E%22%20%2B%20this.oo%20%2B%20%22%3C%2Ftd%3E%3C%2Ftr%3E%22%3B%0A%09}%0A}%0A%0Avar%20team%20%3A%20Personne[]%20%3D%20[]%3B%20%0Ateam.push%28new%20Personne%28%22thomas%22%2C%22bous%22%2Ctrue%29%29%3B%0Ateam.push%28new%20Personne%28%22thomas2%22%2C%22bous2%22%29%29%3B%0A%2F*%0Aalert%28team[0].prenom%29%3B%0Aalert%28team[0].oo%29%3B%0A%0Aalert%28team[1].prenom%29%3B%0Aalert%28team[1].oo%29%3B*%2F%0A%0A%0Ateam[1].show%28%29%3B%0A%0A
