# cigarParty

public boolean cigarParty(int cigars, boolean isWeekend) {
  if((cigars >= 40) && (cigars <=60)){
    return true;
}
  else if((isWeekend == true) && (cigars >= 40)){
    return true;
  }
  else {return false;
}
}
