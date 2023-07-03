# Mixamo2Unreal
A central place for Mixamo IK rigs and IK retargeters for Unreal Engine 5.2+ 

## Getting Started
1. Download the project and open it in unreal engine 5.2+
2. Open the Content folder and choose the retargeter you want (currently there is only a Mixamo to Metahuman retargeter. Soon I will have Mixamo to UE5 Manny [External contributions are very welcome!!])

## Setting up retargeter
4. Right click on the retargeter and choose migrate, and select the folder of the project you need the retargeter in. Unreal will automatically bring along the mixamo skeleton and its IK rig, along with the skeleton and IK rig of the target.
5. In your project you just migrated the retargeter to, import your Mixamo animations, setting the skeleton to the Mixamo skeleton.
6. Now you can open RTG_MixamoTo(TARGET HERE) and select the target skeleton. Especially in cases of metahumans, you'll likely need to set the target skeleton manually to the one that was already in your project. Otherwise Unreal won't register that the preset target is exactly the same as the one in your project.
7. Choose your mixamo animations and watch it also show up on your target skeleton.

## Done!
And you're done!
If you have any improvements or requests please feel free to use the Issues and/or pull request your own fork. 
