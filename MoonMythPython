# This is a collection of the custom python code used throughout Moon & Myth

#Hand Tracking Location & Trigger

    # Location:

    2 if (400 <= op('datto1')['chan1'] <= 550 and 500 <= op('datto1')['chan2'] <= 600) else 3 if (350 <= op('datto1')['chan1'] <= 850 and 150 <= op('datto1')['chan2'] <= 400) else 4 if (560 <= op('datto1')['chan1'] <= 820 and 450 <= op('datto1')['chan2'] <= 600) else 0

    # Trigger:

    1 if (400 <= op('datto1')['chan1'] <= 550 and 500 <= op('datto1')['chan2'] <= 600) or (350 <= op('datto1')['chan1'] <= 850 and 150 <= op('datto1')['chan2'] <= 400) or (560 <= op('datto1')['chan1'] <= 820 and 450 <= op('datto1')['chan2'] <= 600) else 0

#Scene Reload 

    1 if (parent(3).op('sceneChanger').par.Currentscene == VALUE) else 0
    #change VALUE depending on sceneChanger

#audioMovie1 - selecting the movie file in TOP based on sceneChanger value

    parent(2).op('base_graphics/base_scenes/scene2/moviefilein1') if (parent(2).op('base_graphics/sceneChanger').par.Currentscene==2) else parent(2).op('base_graphics/base_scenes/scene3/moviefilein1')  if (parent(2).op('base_graphics/sceneChanger').par.Currentscene==3) else parent(2).op('base_graphics/base_scenes/scene4/moviefilein1')  if (parent(2).op('base_graphics/sceneChanger').par.Currentscene==4) else parent(2).op('base_graphics/base_scenes/scene1/moviefilein1') 