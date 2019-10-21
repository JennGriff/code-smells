### Dead Code

'Text' is defined but never used.

```{JavaScript}
import { View, Text, StyleSheet, FlatList, Button } from "react-native";
}
```

void Submit() was used for testing but is no longer in use

```{Dart}
void Submit() {
  print("Sup");
}
```

Many have been imported, but few have been used. 

```{JavaScript}
// Unused libraries that were abandoned

import Collapsible from 'react-native-collapsible';
import {
    Accordion,
    AccordionItem,
    AccordionItemButton,
    AccordionItemHeading,
    AccordionItemPanel,
} from 'react-accessible-accordion';

```
