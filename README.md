# c55
https://snack.expo.dev/@savio26/appdjmixeretapa-1-modelo
<View>
          <TouchableOpacity
            style={{
               width: 200,
              height: 100,
              justifyContent: 'center',
              alignItems: 'center',
              borderRadius: 100,
              backgroundColor: 'green',
              borderWidth: 2,
              borderColor: 'white',
              marginTop:20
            }}
            onPress={() => {
              var url =
                'https://d1490khl9dq1ow.cloudfront.net/audio/music/mp3preview/BsTwCwBHBjzwub4i4/bright-and-breezy-music-bed_MJA8hSHO_NWM.mp3';
              this.playSound(url);
            }}>
            <Text> Som 4</Text>
          </TouchableOpacity>
        </View>
        
        <TouchableOpacity
          style={{
            width: 200,
            height: 50,            
            justifyContent: 'center',
            alignItems: 'center',
            borderRadius: 30,
            backgroundColor: 'red',
            borderWidth: 2,
            borderColor: 'white',
            marginTop:40
          }}
          onPress={() => {
             Audio.setIsEnabledAsync(false);
          }}>
          <Text> Parar Som </Text>
        </TouchableOpacity>
      </View>
    );
  }
