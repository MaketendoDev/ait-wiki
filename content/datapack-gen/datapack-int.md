---
title: Customizing TARDIS
type: docs
---

hi
<html>
    <head>
        <div>
            <div id="packFormContainer">
                <h1 style="font-family: 'Verdana', sans-serif; font-weight: bold; color: #2d76a2;"><a href="https://pavatus.github.io/ait-wiki/datapacks/interiors/">Datapack Desktop</a></h1>
        
                <form id="packForm">
                    <label for="namespace">Namespace:</label>
                    <input type="text" id="namespace" name="namespace" required><br><br>
    
                    <label for="id">ID:</label>
                    <input type="text" id="id" name="id" required><br><br>
    
                    <label for="nbtFile">Structure file:</label>
                    <input type="file" id="nbtFile" accept=".nbt" required><br><br>
    
                    <h2 class="optional-header">Optional</h2>
                    <label for="pngFile">Preview image:</label>
                    <input type="file" id="pngFile" accept=".png"><br><br>

                    <button type="button" onclick="createZip()">Create</button>
                </form>
            </div>

            <script src="https://cdnjs.cloudflare.com/ajax/libs/jszip/3.7.1/jszip.min.js"></script>
            <script src="https://cdnjs.cloudflare.com/ajax/libs/FileSaver.js/2.0.5/FileSaver.min.js"></script>
            <script src="main.js"></script>
        </div>
    </head>
</html>