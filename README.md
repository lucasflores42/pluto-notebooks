julia > ]  
julia > add PlutoSliderServer#static-export-1  
julia > using PlutoSliderServer  
julia > PlutoSliderServer.export_notebook("/path/notebook.jl"; Precompute_enabled=true, Precompute_max_filesize_per_group=1e9, Export_create_index=true)  
