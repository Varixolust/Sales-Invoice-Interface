// Sales-Invoice-Interface
//Use Java Swing application to design this
//Requirements
//See attach file on issue tab
//Code Below


      
DefaultTableModel model;
    String itemCode,itemDescription;
    int qty;
    double total, price;
    
    ArrayList<String> itemcode = new ArrayList<>();
    ArrayList<Integer> quantity = new ArrayList<>();
    ArrayList <String> description = new ArrayList<>();
    ArrayList <Double> rate = new ArrayList<>();
    ArrayList <Double> itemTotal = new ArrayList<>();


        jTable1.setBorder(new javax.swing.border.SoftBevelBorder(javax.swing.border.BevelBorder.RAISED));
        jTable1.setFont(new java.awt.Font("Tahoma", 1, 11)); // NOI18N
        jTable1.setModel(new javax.swing.table.DefaultTableModel(
            new Object [][] {

            },
            new String [] {
                "Item Code", "Item Description", "Price (FJD $)", "Qty", "Total (FJD $)"
            }
        ) {
            Class[] types = new Class [] {
                java.lang.String.class, java.lang.String.class, java.lang.Float.class, java.lang.Integer.class, java.lang.Float.class
            };

            public Class getColumnClass(int columnIndex) {
                return types [columnIndex];
            }
        });
        jScrollPane1.setViewportView(jTable1);



 qty = Integer.parseInt(txtQty1.getText());
       
       
       model = (DefaultTableModel)jTable1.getModel();
       
     
       model.addRow(new Object []
               
      {
      itemCode,
      itemDescription,
      price,
      qty,
      total,
     
      
      } );

        
    }   

