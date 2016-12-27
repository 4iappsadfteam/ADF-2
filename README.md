
valueChangeEvent:
********************************************************************************************
    public void inputImage(ValueChangeEvent valueChangeEvent) {
        // Add event code here...
        if(valueChangeEvent!=null){
            UploadedFile filevalue=(UploadedFile)valueChangeEvent.getNewValue();
            AdfFacesContext.getCurrentInstance().getViewScope().put("fileobj", filevalue);
        }
        }
        
********************************************************************************************
       AdfFacesContext.getCurrentInstance().getViewScope().get("fileobj");
********************************************************************************************
       
       
